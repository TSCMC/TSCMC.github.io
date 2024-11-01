# TSCMC.github.io
The website for TSC Minecraft server

## How to add pages
Click "Add file" and select "Create new file"

At "Name your file..." box, put the name of the page that you want to be the URL and end it with `.md`
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
since it's just a markdown file, so it uses similar formatting to discord (with some exception but don't worry about that)

## File naming rules

- File names should only contain lower case alphanumeric characters or dashes.
- File names should not contain non-ascii characters.
- File names should not have spaces in them. If you have multi-word names, please connect them with dashes.
- Example: `Why Central` -> `why-central`

## Folder Structure

```
Root
index.md
- rail-lines
  - lacon-main-line
  - nex-ender-line
  - nex-t-train-line
  - north-south-rail
  - [some-other-line]
- rail-stations
  - why-central
  - squid-farm
  - froglight-farm
  - shin-akiyama
  - southern-highlands
  - [some other station]
- rail-networks
  - lacon
  - nex
  - yuitrans
  - volans
  - [some other system]
- [some other category TBA]
```

## Disclaimer
NOT AN OFFICIAL MINECRAFT SERVICE. NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT.
