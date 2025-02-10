---
layout: default
title: TSC Minecraft Knowledge Base
description: Information related to the TSC Minecraft server
---
# TSC Minecraft Knowledge Base

Information related to the TSC Minecraft server will be written on this website!

## Pages on this website

{% assign pages = site.pages | where_exp: 'page', 'page.title' %}

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
- [{{page.title}}]({{page.url}})
{% endif -%}
{% endfor %}

### Rail Lines

{% for page in pages -%}
{% if page.url contains "/rail-lines" -%}
- [{{page.title}}]({{page.url}})
{% endif -%}
{% endfor %}

### Rail Stations

{: style="columns:2;-webkit-columns:2;-moz-columns:2;"}
{% for page in pages -%}
{% if page.url contains "/rail-stations" -%}
- [{{page.title}}]({{page.url}})
{% endif -%}
{% endfor %}

## Transit Map

This is the overall transit map of the TSC Minecraft server:

{%
include imagelightbox.html
imgname="transitmap"
imglink="/assets/img/map.png"
imgcaption="Overworld & Nether Railways of the TSC Minecraft Server"
%}

[View original](/assets/img/map.png "Click to view in original size")
[View legacy map](/assets/img/map-legacy.png "Click to view old version by Sunoka")
{: style="text-align:center; font-size:0.75em;"}
