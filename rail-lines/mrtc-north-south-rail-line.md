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
station or South Spawn station, had opened since 7th May 2024 with active
service to Moss Vale, prior to the commencement of NSR service.

### YuiTrans

YuiTrans, the rail authority of the Empire of Shin-Akiyama owns and manages MRTC
rail in the Shin-Akiyama region. The connection between Bundanoon station and
Shin-Akiyama station was completed and operational on 27th May 2024.

### Fulahm Railways

Fulahm Railways (FR), the rail authority of the Council of Paddy Fields owns and
manages MRTC rail in the Shinonome region. The connection between Shin-Akiyama
station and Shinonome-Chuo station is currently under construction.

## Stations

Connecting lines currently under construction or planned are italicized,
transfer to lines in separate station nearby are marked with the :transfer:
emoji, transfer to lines via nether portal are marked with the :nether: emoji,
and connection to other transport modes are marked with either the :anchor:
emoji if it's by sea or the :airplane: emoji if it's by air.

{% capture nsrtaxevasionchalet %}
● Crêpobeur Funicular Line<br/>
● :pfl: *[FR Paddy Field Line](/rail-lines/fr-paddy-field-line)*<br/>
● :tml: *YuiTrans Tenma Line*
{% endcapture %}

{% capture nsrministryoflove %}
● :ewr: [MRTC East-West Rail](/rail-lines/mrtc-east-west-rail-line)<br/>
● :nether: YuiTrans Shin-Tenma Line<br/>
● :tml: *YuiTrans Tenma Line*
{% endcapture %}

{% capture nsrwhycentral -%}
● :ewr: [MRTC East-West Rail](/rail-lines/mrtc-east-west-rail-line)<br/>
● :ael: RR Airport Express<br/>
● :pfl: [FR Paddy Field Line](/rail-lines/fr-paddy-field-line)<br/>
● :volans: Volans Minecart Line<br/>
● :tml: YuiTrans Tenma Line<br/>
● Alhambra Railway Main Line<br/>
● Spider Farm Shuttle<br/>
● :transfer::lacon: [Lacon Main Line](/rail-lines/lcn-main-line)<br/>
● :transfer::lacon: [Shin-Lacon Main Line](/rail-lines/slcn-main-line)<br/>
● :nether: [NEX Ender Line](/rail-lines/nex-ender-line)<br/>
● :nether: [NEX T-Train Line](/rail-lines/nex-t-train-line)<br/>
● :nether: YuiTrans Shin-Tenma Line<br/>
● *YJHSR Yayajima Express*
{%- endcapture %}

{% capture nsrcordeliacross %}
● [SHR Loop Metro Line](/rail-lines/shr-loop-line)<br/>
● *YuiTrans Mochizuki Line*<br/>
● *FR Name Pending Line*
{% endcapture %}

{% capture nsrmossvale %}
● [SHR Western Line](/rail-lines/shr-western-line)<br/>
● [SHR Loop Metro Line](/rail-lines/shr-loop-line)<br/>
● [SHR Meadowbank Metro Line](/rail-lines/shr-meadowbank-line)<br/>
● [SHR Southern Metro Line](/rail-lines/shr-southern-line)<br/>
● :nether: [NEX Ender Line](/rail-lines/nex-ender-line)
{% endcapture %}

{% capture nsrbundanoon %}
● RR Yuuhi Line<br/>
● *YuiTrans LRT Iori Line*<br/>
● *YuiTrans Mochizuki Line*<br/>
{% endcapture %}

{% capture nsrshinakiyama %}
● :tml: YuiTrans Tenma Line<br/>
● YuiTrans LRT Mio Line<br/>
● :lacon: [Lacon Industry Line](/rail-lines/lcn-industry-line)<br/>
● :pfl: [FR Paddy Field Line](/rail-lines/fr-paddy-field-line)<br/>
● RR Yuuhi Line<br/>
● SR Alpha Line<br/>
● :nether: [NEX Ender Line](/rail-lines/nex-ender-line)<br/>
● :nether: YuiTrans Shin-Tenma Line<br/>
● *YuiTrans Hinomori Line*<br/>
● *YuiTrans Mochizuki Line*<br/>
● *YuiTrans LRT Iori Line*<br/>
● *YJHSR Yayajima Express*
{% endcapture %}

{% capture nsrshinonomechuo %}
● FR Asahina Line<br/>
● YuiTrans LRT Mio Line
{% endcapture %}

| Station name | Opened | Connections | Locality | Managed by |
|:---:|:---:|:---|:---:|:---:|
| Tax Evasion Chalet | 2024-09-22 | {{ nsrtaxevasionchalet | strip_newlines }} | Tax Evasion Chalet | MRTC |
| Ministry of Love | 2024-05-12 | {{ nsrministryoflove | strip_newlines }} | Villager Breeder | MRTC |
| [WHY Central](/rail-stations/why-central) | 2024-05-04 | {{ nsrwhycentral | strip_newlines }} | Spawn | MRTC |
| Sandy Beach | 2024-05-08 | ● :tml: *YuiTrans Tenma Line* | Sandy Beach | MRTC |
| Cordelia Cross | 2024-05-07 | {{ nsrcordeliacross | strip_newlines }} | Cordelia Cross | SHR |
| [Moss Vale](/rail-stations/moss-vale) | 2024-05-03 | {{ nsrmossvale | strip_newlines }} | Moss Vale | SHR |
| Bundanoon | 2024-05-06 | {{ nsrbundanoon | strip_newlines }} | Bundanoon | SHR |
| [Shin-Akiyama](/rail-stations/shin-akiyama) | 2024-05-27 | {{ nsrshinakiyama | strip_newlines }} | Shin-Akiyama | YuiTrans |
| *Shinonome-Chuo* | upcoming | {{ nsrshinonomechuo | strip_newlines}} | Shinonome | FR |
| *[Name pending]* | upcoming | ● *[SHR Western Line](/rail-lines/shr-western-line)* | *[Name pending]* | TBD |

Note: TBD = to be decided
