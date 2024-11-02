---
layout: default
title: Nether Express
description: Nether Express
---

# Nether Express

Nether Express (NEX) is a rail network that provides fast travel throughout the
server via the nether.

## Lines

{% for page in pages -%}
{% if page.url contains "/rail-lines/nex-" -%}

- [{{page.title}}]({{page.url}})

{% endif -%}
{% endfor %}

- Spratly Line (Planned)

## Shuttle Services

- Witch Farm Shuttle
- Spider Farm Shuttle
