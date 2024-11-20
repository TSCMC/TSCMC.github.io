---
layout: default
title: MRTC East-West Rail Line
description: Mainline Railway Transit Corporation East-West Rail Line
---

{% capture mrtcewrinfo %}
![The icon of EWR <>](/assets/img/rail-lines/64px/mrtc-east-west-rail.png
"The icon of East-West Rail line")

Network | Mainline Railway<br/>Transit Corporation<br/>(Mainline Section)<br/>RichardRail<br/>(North Branch)
Line Colour | Name: Light Green<br/>Sign: &a<br/>Wool: Light Green<br/>HTML: `5DFF60`
First opened | 2024-05-12<br/>(WHY Central -<br/>Ministry of Love)
Last extension | 2024-10-10<br/>(Shirokane -<br/>Port Watanabe)
{% endcapture %}
{%
  include infobox.html
  infoboxid="eastwestrail"
  infoboxname="East-West Rail"
  infoboxcontent=mrtcewrinfo
%}

# East-West Rail (EWR)

The East-West Rail (EWR) Line is a mainline rail of the
[Mainline Railway Transit Corporation](/rail-networks/mrt) (MRTC).
This heavy rail line aims to connect areas and settlements on the east of spawn
to the west, being a backbone of server-wide coverage on the game's X axis.

Despite the rail connects up to Dobrzanka with construction being carried out in
several places for eastward extension, there are still some single-tracked
section between Cavern Junction Station and Haruyama Station due to ongoing
building constructions in the area limitting the rail's double-tracking effort.
However, to avoid disruptions and collision, rail passing loops are installed at
several key locations.

## Through-running rail

The rail line through-run on rail sections that were built, owned and managed by
different entities.

### RichardRail

RichardRail (RR) owns and manages MRTC rail in the regions of Otomune, Ayase,
Sakurauchi, New Taichung, Richardsbay, Shirokane, and Port Watanabe. The
connection between [WHY Central Station](/rail-stations/why-central) and
Otomune Station was completed and operational on 31st May 2024, before the rail
gets extended westward.

The first train from [WHY Central Station](/rail-stations/why-central)
officially departed to Otomune Station on the same day. Otomune Station was
known at the time as Mochizuki Station but the station name was changed to avoid
confusion between the station and a different railway line currently under
planning, YuiTrans Mochizuki Line.

In addition to owning and managing the MRTC mainline section in the regions
aforementioned, RichardRail also owns and manages the shuttle train service,
East-West Rail North Branch from Otomune Station to Richardsbay Central Station.
Unlike the mainline where MRTC operates the train with RichardRail managing the
rail, this branch is wholly operated and managed by RichardRail.

### Yayajima High Speed Rail Incorporated

Yayajima High Speed Rail Incorporated (YJHSR Inc), a subsidiary wholly owned by
the Yayajima City Council (YJCC), owns and manages MRTC rail in the
[City of Yayajima](/areas/ucl/yayajima). The connection between Ministry of Trade
Station and [Yayajima North Station](/rail-stations/yayajima-north) was
completed and operational on 8th July 2024. The first train from Ministry of
Trade Station officially departed to Dobrzanka Station, the terminus of the
East-West Rail at the time, passing by
[Yayajima North Station](/rail-stations/yayajima-north) on the same day.

### Dobrzanka Authority

Dobrzanka Authority (DA) of the Dobrzanka region owns and manages MRTC rail in
said region. The connection between
[Yayajima North Station](/rail-stations/yayajima-north) and Dobrzanka Station
was completed and operational on 8th July 2024. The first train from
[Yayajima North Station](/rail-stations/yayajima-north) officially departed to
Dobrzanka Station on the same day.

### Lacon Railway

[Lacon Railway](/rail-networks/lcn) owns and manages a section of MRTC rail that
has been built as standalone tracks in a shared right-of-way (ROW) with the
existing [Shin-Lacon Dongbu Line](/rail-lines/slcn-dongbu-line) and Sancheon
Rapid Beta Line. The line serves as the local service in the shared section,
with both the Dongbu Line and SR Beta serving as express.
<br>Due to the complex operating and management structure of this section, it is
separately managed by **Dongbuline Management Corp.**, a subsidiary of Lacon.

## Stations

To make it easier to follow, the stations list here are listed from west to east
instead of from east to west, because most people are acustomed to imagining
something from left to right due to the prevalent writing direction being left
to right.

Connecting lines currently under construction or planned are italicized,
transfer to lines in separate station nearby are marked with the :transfer:
emoji, transfer to lines via nether portal are marked with the :nether: emoji,
and connection to other transport modes are marked with either the :anchor:
emoji if it's by sea or the :airplane: emoji if it's by air.

### Mainline Station

This train service is run by MRTC. 

{% capture ewrnamepending1 %}
● :ael: *RR Airport Express*<br/>
● *RR Yuuhi Line*
{% endcapture %}

{% capture ewrportwatanabe %}
● RR Aratani Line<br/>
● :anchor: *RichardCorp Boat Rapid Transit*
{% endcapture %}

{% capture ewrshirokane %}
● :ael: RR Airport Express<br/>
● RR Aratani Line
{% endcapture %}

{% capture ewrotomune %}
● RR East-West Rail North Branch<br/>
● *RR Light Line*<br/>
● *YJHSR Yayajima Express*
{% endcapture %}

{% capture ewrbowralerbrug %}
● :volans: Volans Minecart Line<br/>
● :transfer: [SHR Meadowbank Metro Line](/rail-lines/shr-meadowbank-line)
{% endcapture %}

{% capture ewrwhycentral -%}
● :nsr: [MRTC North-South Rail](/rail-lines/mrtc-north-south-rail-line)<br/>
● :ael: RR Airport Express<br/>
● :pfl: [FR Paddy Field Line](/rail-lines/fr-paddy-field-line)<br/>
● :volans: Volans Minecart Line<br/>
● :tml: YuiTrans Tenma Line<br/>
● Alhambra Main Line<br/>
● :transfer::lacon: [Lacon Main Line](/rail-lines/lcn-main-line)<br/>
● :transfer::lacon: [Shin-Lacon Main Line](/rail-lines/slcn-main-line)<br/>
● :transfer: [NEX Spider Farm Shuttle](/rail-lines/nex-spider-farm-shuttle)<br/>
● :nether: [NEX Ender Line](/rail-lines/nex-ender-line)<br/>
● :nether: [NEX T-Train Line](/rail-lines/nex-t-train-line)<br/>
● :nether: YuiTrans Shin-Tenma Line<br/>
● *YJHSR Yayajima Express*
{%- endcapture %}

{% capture ewrministryoflove %}
● :nsr: [MRTC North-South Rail](/rail-lines/mrtc-north-south-rail-line)<br/>
● :nether: YuiTrans Shin-Tenma Line<br/>
● :tml: *YuiTrans Tenma Line*
{% endcapture %}

{% capture ewrministryoftrade %}
● Alhambra Main Line<br/>
● :transfer: [Shin-Lacon Seobu Line](/rail-lines/slcn-seobu-line)<br/>
● *YuiTrans Tenma Line*
{% endcapture %}

{% capture ewryayajimanorth %}
● :lacon: [Lacon Main Line](/rail-lines/lcn-main-line)<br/>
● *YajiMetro Lingkaran Line*<br/>
● *YajiTram Putri Line*
{% endcapture %}

{% capture ewrstronghold %}
● :lacon: [Shin-Lacon Dongbu Line](/rail-lines/slcn-dongbu-line)<br/>
● :lacon: Sancheon Rapid Beta<br/>
● :nether: [NEX Ender Line](/rail-lines/nex-ender-line)<br/>
● :nether: [NEX T-Train Line](/rail-lines/nex-t-train-line)<br/>
● :nether: :lacon: Lacon Sancheonville Shuttle
{% endcapture %}

{% capture ewrgonghangap %}
● :lacon: [Shin-Lacon Dongbu Line](/rail-lines/slcn-dongbu-line)<br/>
● :lacon: Sancheon Rapid Beta<br/>
● :lacon::airplane: Lacon Airport
{% endcapture %}

{% capture ewrbanho %}
● :lacon: [Shin-Lacon Dongbu Line](/rail-lines/slcn-dongbu-line)<br/>
● :lacon: Banho Harbor Shuttle
{% endcapture %}

{% capture ewrguardianfarm %}
● [NEX Nowhere Line](/rail-lines/nex-nowhere-line)<br/>
● :nether: [NEX Ender Line](/rail-lines/nex-ender-line)<br/>
● :lacon: *Sancheon Rapid Beta*
{% endcapture %}

| Station name | Opened | Connections | Locality | Managed by |
|:---:|:---:|:---|:---:|:---:|
| *[Name pending]* | upcoming | {{ ewrnamepending1 | strip_newlines}} | *[Name pending]* | RR |
| Port Watanabe | 2024-10-10 | {{ ewrportwatanabe | strip_newlines}} | Port Watanabe | RR |
| Shirokane | 2024-10-09 | {{ ewrshirokane | strip_newlines}} | Shirokane | RR |
| New Taichung<br/>Gateway | 2024-10-08 | ● :nether: [NEX T-Train Line](/rail-lines/nex-t-train-line) | New Taichung<br/>(in Nether) | RR |
| Sakurauchi | 2024-06-02 | ● :trl: RR Trunk Line | Sakurauchi | RR |
| North Mittagong | 2024-06-02 | ● RR Mittagong Peoplemover | Mittagong | RR |
| Otomune | 2024-05-31 | {{ ewrotomune | strip_newlines}} | Otomune | RR |
| Bowralerbrug | 2024-06-01 | {{ ewrbowralerbrug | strip_newlines}} | Bowralerbrug | RR |
| [WHY Central](/rail-stations/why-central) | 2024-05-04 | {{ ewrwhycentral | strip_newlines }} | Spawn | MRTC |
| Ministry of Love | 2024-05-12 | {{ ewrministryoflove | strip_newlines }} | Villager Breeder | MRTC |
| Ministry of Trade | 2024-06-08 | {{ ewrministryoftrade | strip_newlines }} | Trading Hall | MRTC |
| Cavern Junction | 2024-09-25 | - | Cavern Junction | MRTC |
| *Gaung Lahar* | upcoming | ● :lacon: [Shin-Lacon Main Line](/rail-lines/slcn-main-line) | Gaung Lahar | MRTC |
| Yayajima North | 2024-06-04 | {{ ewryayajimanorth | strip_newlines }} | Yayajima | YJHSR |
| *Yayajima Lighthouse* | upcoming | - | Yayajima | YJHSR |
| Haruyama | 2024-10-07 | ● :lacon: [Lacon Sancheonville Line](/rail-lines/lcn-sancheonville-line) | Haruyama | MRTC |
| Dobrzanka | 2024-06-17 | ● :lacon: *Sancheon Rapid Alpha Line* | Dobrzanka | DA |
| [Stronghold](/rail-stations/stronghold) | 2024-11-15 | {{ ewrstronghold | strip_newlines }} | Stronghold | Lacon |
| [Maguro Lake](/rail-stations/maguro-lake) | 2024-11-15 | | Maguro Lake | Dongbuline Management Corp. |
| Jajak Forest | 2024-11-15 | | - | Dongbuline Management Corp. |
| Gonghang-Ap | 2024-11-15 | {{ ewrgonghangap | strip_newlines }} | Lacon Airport | Dongbuline Management Corp. |
| Airport Long-term Parking | 2024-11-15 | | Lacon Airport | Dongbuline Management Corp. |
| ! | 2024-11-15 | | ! | Dongbuline Management Corp. |
| Banho | upcoming | {{ ewrbanho | strip_newlines }} | Banho | Dongbuline Management Corp. |
| *[Name pending]* | upcoming | - | *[Name pending]* | Lacon |
| *[Guardian Farm](/rail-stations/guardian-farm)* | upcoming | {{ ewrguardianfarm | strip_newlines }} | Guardian Farm | Lacon |
| *[Name pending]* | upcoming | - | *[Name pending]* (around 3445,-398) | MRTC |
| *[Name pending]* | upcoming | - | *[Name pending]* (around 3494,-565) | MRTC |
| *[Name pending]* | upcoming | - | *[Name pending]* (around 4034,-776) | MRTC |
| *[Name pending]* | upcoming | - | *[Name pending]* (around 4566,-1412) | MRTC |
| *Gurun* | upcoming | - | *Gurun* | MRTC |
| *[Name pending]* | upcoming | - | *[Name pending]* (around 5617,-1992) | MRTC |
| *[Name pending]* | upcoming | - | *[Name pending]* (around 6307,-2031) | MRTC |
| *Mycellium Delight* | upcoming | ● :nether: *[NEX Ender Line](/rail-lines/nex-ender-line)* | Mycellium Delight | MRTC |

Note: TBD = to be determined

### Branch Station

#### East-West Rail North Branch

This train service is run by RichardRail.

{% capture ewrnbrbc %}
● :ael: RR Airport Express<br/>
● :trl: RR Trunk Line
{% endcapture %}

{% capture ewrnbaap %}
● :ael: RR Airport Express<br/>
● :airplane: Ayase Airport
{% endcapture %}

{% capture ewrnbotomune %}
● :ewr: East-West Rail<br/>
● *RR Light Line*<br/>
● *YJHSR Yayajima Express*
{% endcapture %}

| Station name | Opened | Connections | Locality | Managed by |
|:---:|:---:|:---|:---:|:---:|
| *Takehama* | upcoming | ● *RR Aratani Line* | *Takehama* | RR |
| *[Name pending]* | upcoming | - | *[Name pending]* | RR |
| Richardsbay Central | 2024-06-01 | {{ ewrnbrbc | strip_newlines}} | Richardsbay | RR |
| *Aoumabashi* | upcoming | ● *RR Light Line* | Aoumabashi | RR |
| Ayase Airport | 2024-06-01 | {{ ewrnbaap | strip_newlines}} | Ayase | RR |
| Otomune | 2024-05-31 | {{ ewrnbotomune | strip_newlines}} | Otomune | RR |
