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

|    Code    |                                     Emoji                                          |              Description             |
|:----------:|:----------------------------------------------------------------------------------:|:-------------------------------------|
| `:lacon:`  | ![:lacon:](/assets/img/rail-networks/24px/lacon-network-white-background.png)      | Lacon Railway                        |
| `:volans:` | ![:volans:](/assets/img/rail-networks/24px/volans-railway.png)                     | Volans Railway                       |
| `:mrtc:`   | ![:mrtc:](/assets/img/rail-networks/24px/mainline-railway-transit-corporation.png) | Mainline Railway Transit Corporation |
| `:nsr:`    | ![:nsr:](/assets/img/rail-lines/24px/mrtc-north-south-rail.png)                    | MRTC North-South Rail Line           |
| `:ewr:`    | ![:ewr:](/assets/img/rail-lines/24px/mrtc-east-west-rail.png)                      | MRTC East-West Rail Line             |
| `:trl:`    | ![:trl:](/assets/img/rail-lines/24px/richardrail-trunk-line.png)                   | RR Trunk Line                        |
| `:ael:`    | ![:ael:](/assets/img/rail-lines/24px/richardrail-airport-express-line.png)         | RR Airport Express Line              |
| `:pfl:`    | ![:pfl:](/assets/img/rail-lines/24px/fulahm-railways-paddy-field-line.png)         | FR Paddy Field Line                  |
| `:tml:`    | ![:tml:](/assets/img/rail-lines/24px/yuitrans-tenma-line.png)                      | YuiTrans Tenma Line                  |

### Using image with custom size

Include this snippet and replace the appropriate text accordingly

```
{%
  include imagewithattrib.html
  imgalt="Write your alt text here"
  imgsrc="Write the source image URL here"
  imgwidth="Put in the image width"
  imgheight="Put in the image height"
  imgalign="choose between left/right/center"
%}
```

Additional attributes you can use (put them before the last `%}`)
```
  imgtitle="write title text here, basically the text that appear on mouse hover"
  imgloading="choose between lazy/eager"
  imgreferrerpolicy="if you use this then you should know what to write here"
```

### Using admonitions

You can use admonitions on the website, including in Markdown format. The
admonitions are available in 5 types, `note`, `info`, `tip`, `warning`, and
`danger`. They will be displayed like this, in order:

![admonitions](/assets/img/admonitions.png)

To use the admonitions, just use the code block but write the type of the
admonition after the first three backticks, for example, the warning admonition
above would be:

````markdown
```warning
This is a warning that someone should not do something.
```
````

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

The admonitions on the website are generated using the Liquid plugin 
[Jekyll Pure Liquid Admonitions](https://github.com/RichDom2185/jekyll-admonitions).
<br/>
The files `_includes/admonitions.liquid`, `_includes/capturehtml.liquid`
and `_sass/admonitions.scss` came from said plugin.

This website uses the [Font Awesome 6 Free](https://fontawesome.com/download)
icons in several places, especially in admonitions.

NOT AN OFFICIAL MINECRAFT SERVICE. NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR
MICROSOFT.
