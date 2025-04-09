---
layout: default
title: TSC Minecraft Knowledge Base
description: Information related to the TSC Minecraft server
---
# TSC Minecraft Knowledge Base

Information related to the TSC Minecraft server will be written on this website!

## Pages on this website

{% assign pages = site.pages | where_exp: 'page', 'page.title' -%}
{% assign creatednetwork = 0 -%}
{% assign networktodo = "" | split: ", " %}
{% assign allline = 0 -%}
{% assign createdline = 0 -%}
{% assign linetodo = "" | split: ", " %}
{% assign allstation = 0 %}
{% assign createdstation = 0 %}
{% assign uniquestation = "" | split: ", " %}
{% assign stationtodo = "" | split: ", " %}

<!-- markdownlint-disable MD032 -->

### Areas

{% for page in pages -%}
{% if page.url contains "/areas" -%}
- [{{page.title}}]({{page.url}})
{% endif -%}
{% endfor %}

### Rail Networks

{% for page in pages -%}
{% if page.url contains "/rail-networks" -%}
{% assign creatednetwork = creatednetwork | plus: 1 -%}
- [{{page.title}}]({{page.url}})
{% endif -%}
{% endfor %}

{% for networkitem in site.data.rail-metadata.networks -%}
  {% if networkitem.slug == null -%}
    {% assign networktodo = networktodo | push: networkitem.name -%}
  {% endif -%}
{% endfor -%}
{% assign networktodo = networktodo | uniq | sort -%}

{% if creatednetwork != site.data.rail-metadata.networks.size -%}
Note: Pages only exist for {{ creatednetwork }} rail networks out of
{{ site.data.rail-metadata.networks.size }} rail networks that exist on the
server.

<details markdown=1>
<summary>Rail network pages not created yet</summary>

{: style="columns:3;-webkit-columns:3;-moz-columns:3;"}
{% for item in networktodo -%}
- {{ item }}
{% endfor %}
</details>
{% endif -%}

### Rail Lines

{% for page in pages -%}
{% if page.url contains "/rail-lines" -%}
{% assign createdline = createdline | plus: 1 -%}
- [{{page.title}}]({{page.url}})
{% endif -%}
{% endfor %}

{% for networkitem in site.data.rail-metadata.networks -%}
  {% assign allline = allline | plus: networkitem.lines.size -%}
  {% for lineitem in networkitem.lines -%}
    {% if lineitem.slug == null -%}
      {% assign linetodo = linetodo | push: lineitem.name -%}
    {% endif -%}
  {% endfor -%}
{% endfor -%}
{% assign linetodo = linetodo | uniq | sort -%}

{% if createdline != allline -%}
Note: Pages only exist for {{ createdline }} rail lines out of around
{{ allline }} rail lines that are operational, planned, or closed on the server.

<details markdown=1>
<summary>Rail line pages not created yet</summary>

{: style="columns:3;-webkit-columns:3;-moz-columns:3;"}
{% for item in linetodo -%}
- {{ item }}
{% endfor %}
</details>
{% endif -%}

### Rail Stations

{: style="columns:2;-webkit-columns:2;-moz-columns:2;"}
{% for page in pages -%}
{% if page.url contains "/rail-stations" -%}
{% assign createdstation = createdstation | plus: 1 -%}
- [{{page.title}}]({{page.url}})
{% endif -%}
{% endfor %}

{% for networkitem in site.data.rail-metadata.networks -%}
  {% for lineitem in networkitem.lines -%}
    {% for stationitem in lineitem.stations -%}
      {% assign uniquestation = uniquestation | push: stationitem.name -%}
      {% if stationitem.slug == null -%}
        {% assign stationtodo = stationtodo | push: stationitem.name -%}
      {% endif -%}
    {% endfor -%}
  {% endfor -%}
{% endfor -%}
{% assign uniquestation = uniquestation | uniq -%}
{% assign stationtodo = stationtodo | uniq | sort -%}

{% if createdstation != uniquestation.size -%}
Note: Pages only exist for {{ createdstation }} stations out of
{{ uniquestation.size }} rail stations that are operational, planned, or closed
on the server.

<details markdown=1>
<summary>Station pages not created yet</summary>

{: style="columns:3;-webkit-columns:3;-moz-columns:3;"}
{% for item in stationtodo -%}
- {{ item }} Station
{% endfor %}
</details>
{% endif %}

## Transit Map

This is the overall transit map of the TSC Minecraft server:

{%
include imagelightbox.html
imgname="transitmap"
imglink="/assets/img/map.png"
imgcaption="Overworld & Nether Railways of the TSC Minecraft Server"
%}

[View original](/assets/img/map.png "Click to view in original size")<br>
[View legacy map](/assets/img/map-legacy.png "Click to view old version by Sunoka")
{: style="text-align:center; font-size:0.75em;"}
