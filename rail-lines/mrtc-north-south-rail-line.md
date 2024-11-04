---
layout: default
title: MRTC North-South Rail Line
description: Mainline Railway Transit Corporation North-South Rail Line
---

{% capture mrtcnsrinfo %}
![The icon of NSR <>](/assets/img/rail-lines/64px/mrtc-north-south-rail.png
"The icon of North-South Rail line")

Network | Mainline Railway<br/>Transit Corporation
Line Colour | Name: Light Purple<br/>Sign: &d<br/>Wool: Magenta<br/>HTML: `A800A8`
First opened | 2024-05-08<br/>(WHY Central<br/>- Sandy Beach)
Last extension | 2024-09-22<br/>(Ministry of Love -<br/>Tax Evasion Chalet)
{% endcapture %}
{%
  include infobox.html
  infoboxid="northsouthrail"
  infoboxname="North-South Rail"
  infoboxcontent=mrtcnsrinfo
%}

# North-South Rail (NSR)

The North-South Rail (NSR) Line is a mainline rail of the
[Mainline Railway Transit Corporation](/rail-networks/mrt) (MRTC).
This heavy rail line aims to connect areas and settlements on the north of spawn
to the south, being a backbone of server-wide coverage on the game's Z axis.

## Through-running rail

The rail line through-run on rail sections that were built, owned and managed by
different entities.

### Southern Highlands Railway

The [Southern Highlands Railway](/rail-networks/shr) (SHR) owns and manages MRTC
rail in the [Southern Highlands region](/areas/southern-highlands). The
connection between Sandy Beach Station and Moss Vale Station was completed and
operational on 9th May 2024.

The first train from WHY Central officially departed to Bundanoon, the terminus
at the time, on the same day. Cordelia Cross station, formerly Camellia Cross
station or South Spawn station, had been open since 7th May 2024.

### Shin-Akiyama Authority

The Shin-Akiyama Authority (SAA) owns and governs MRTC rail in the Shin-Akiyama
region. The connection between Bundanoon station and Shin-Akiyama station was
completed and operational on 27th May 2024.

## Stations

{% capture nsrwhycentral -%}
● :ewr: MRTC East-West Rail<br/>
● :ael: RR Airport Express<br/>
● :pfl: [FR Paddy Field Line](/rail-lines/fr-paddy-field-line)<br/>
● :volans: Volans Railway Minecart Line<br/>
● :tml: YuiTrans Tenma Line<br/>
● Alhambra Railway Main Line
{%- endcapture %}

{% capture nsrmossvale %}
● [SHR Western Line](/rail-lines/shr-western-line)<br/>
● [SHR Loop Line](/rail-lines/shr-loop-line)<br/>
● [SHR Meadowbank Line](/rail-lines/shr-meadowbank-line)<br/>
● [SHR Southern Line](/rail-lines/shr-southern-line)
{% endcapture %}

{% capture nsrshinakiyama %}
● :tml: YuiTrans Tenma Line<br/>
● YuiTrans LRT Mio Line<br/>
● :lacon: [Lacon Industry Line](/rail-lines/lcn-industry-line)<br/>
● :pfl: [FR Paddy Field Line](/rail-lines/fr-paddy-field-line)<br/>
● RR Yuuhi Line<br/>
● SR Alpha Line
{% endcapture %}

{% capture nsrshinonomechuo %}
● FR Asahina Line<br/>
● YuiTrans LRT Mio Line
{% endcapture %}

| Station name | Opened | Connections | Locality | Managed by |
|:---:|:---:|:---|:---:|:---:|
| Tax Evasion Chalet | 2024-09-22 | Crêpobeur Funicular Line | Tax Evasion Chalet | MRTC |
| Ministry of Love | 2024-05-12 | :ewr: MRTC East-West Rail | Villager Breeder | MRTC |
| [WHY Central](/rail-stations/why-central) | 2024-05-04 | {{ nsrwhycentral | strip_newlines }} | Spawn | MRTC |
| Sandy Beach | 2024-05-08 | YuiTrans Tenma Line | Sandy Beach | MRTC |
| Cordelia Cross | 2024-05-07 | [SHR Loop Line](/rail-lines/shr-loop-line) | Cordelia Cross | SHR |
| [Moss Vale](/rail-stations/moss-vale) | 2024-05-03 | {{ nsrmossvale | strip_newlines }} | Moss Vale | SHR |
| Bundanoon | 2024-05-06 | RR Yuuhi Line | Bundanoon | SHR |
| Shin-Akiyama | 2024-05-27 | {{ nsrshinakiyama | strip_newlines }} | Shin-Akiyama | SAA |
| Shinonome-Chuo | upcoming | {{ nsrshinonomechuo | strip_newlines}} | Shinonome | MRTC |
