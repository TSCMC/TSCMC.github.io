# TSCMC.github.io
The website for TSC Minecraft server

## How to add pages
Click "Add file" and select "Create new file"

At "Name your file..." box, put the name of the page that you want to be the URL
and end it with `.md`
- If you want it to be `https://tscmc.github.io/theland` then it will be `theland.md`
- If you want it to be `https://tscmc.github.io/land/farm` then it will be `land/farm.md`

In the big text box, starts it with
```markdown
---
layout: default
title: insert the title of the page
description: insert the description of the page
---
```

and below that write like how you would do on discord
(ie. using # for title, using \[text\]\(link\) for links, \* for italic, etc)

since it's just a markdown file, it uses similar formatting to discord (with
some exception but don't worry about that)

### How to align images

Custom CSS has been added that allows you to align float image on the website.

Just put `<` in the image name to align the float to the left, `>` for right,
and `<>` for center. For example:
- `![Some Logo >](/assets/img/logo.png "The logo")` will align float Some Logo
  to the right side
- `![Some Logo <](/assets/img/logo.png "The logo")` will align float Some Logo
  to the left side

### Using emoji in website

The website has jemoji installed, so you can use default emoji on Discord the
same way on the website as well. For example, writing `:thumbsup:` on the
website will give you :thumbsup: the same way as on Discord.

There are also additional custom emoji added using
[imojify](https://github.com/danielthepope/imojify) that you can use on
the website, those are listed as follow:

| Emoji name | Emoji image                                                                   |
|    :---:   |    :---:                                                                      |
| `:lacon:`  | ![:lacon:](/assets/img/rail-networks/64px/lacon-network-white-background.png) |
| `:volans:` | ![:volans:](/assets/img/rail-networks/64px/volans-railway.png)                |
|  `:nsr:`   | ![:nsr:](/assets/img/rail-lines/64px/mrtc-north-south-rail.png)               |
|  `:ewr:`   | ![:ewr:](/assets/img/rail-lines/64px/mrtc-east-west-rail.png)                 |
|  `:trl:`   | ![:trl:](/assets/img/rail-lines/64px/richardrail-trunk-line.png)              |
|  `:ael:`   | ![:ael:](/assets/img/rail-lines/64px/richardrail-airport-express-line.png)    |
|  `:pfl:`   | ![:pfl:](/assets/img/rail-lines/64px/fulahm-railways-paddy-field-line.png)    |
|  `:tml:`   | ![:tml:](/assets/img/rail-lines/64px/yuitrans-tenma-line.png)                 |

## File naming rules

- File names should only contain lower case alphanumeric characters or dashes.
- File names should not contain non-ascii characters.
- File names should not have spaces in them. If you have multi-word names,
  please connect them with dashes.
- Example: `Why Central` -> `why-central`

## Folder Structure

```
Root
index.md
- areas
  - fmcity
  - yayajima
  - [some other area]
- rail-networks
  - lacon
  - nex
  - yuitrans
  - volans
  - [some other system]
- rail-lines
  - lacon-main-line
  - nex-ender-line
  - nex-t-train-line
  - north-south-rail
  - [some other line]
- rail-stations
  - why-central
  - squid-farm
  - froglight-farm
  - shin-akiyama
  - southern-highlands
  - [some other station]
- [some other category TBA]
```

## Disclaimer
NOT AN OFFICIAL MINECRAFT SERVICE. NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT.
