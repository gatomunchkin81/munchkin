---
layout: default
title: Mapa del sitio
permalink: /sitemap/
nav_exclude: true
description: "Mapa de contenidos de Gato Munchkin: historia, genética, salud, cría responsable, reconocimiento felino e investigación."
---

# Mapa del sitio

Explora los contenidos publicados en **Gato Munchkin**, organizados por secciones.

{% assign main_pages = site.pages
  | where_exp: "item", "item.nav_order != nil"
  | where_exp: "item", "item.parent == nil"
  | sort: "nav_order" %}

{% for section in main_pages %}

## [{{ section.title }}]({{ section.url | relative_url }})

{% assign children = site.pages
  | where: "parent", section.title
  | sort: "nav_order" %}

{% for child in children %}

- [{{ child.title }}]({{ child.url | relative_url }})
{% endfor %}

{% endfor %}

---

Este mapa se genera a partir de las páginas del sitio.

Para los rastreadores y buscadores, también está disponible el [mapa XML]({{ '/sitemap.xml' | relative_url }}).
