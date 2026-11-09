---
layout: default
title: Mapa del sitio
permalink: /sitemap/
nav_exclude: true
description: "Mapa completo de Gato Munchkin: raza, historia, genética, salud, cría responsable, Minuet, Bambino, artículos científicos y quiénes somos."
---

# Mapa del sitio

Explora los contenidos publicados en **Gato Munchkin**, organizados por secciones.

Este mapa se actualiza automáticamente a partir de la estructura de las páginas del sitio.

{% assign main_pages = site.pages
  | where_exp: "item", "item.nav_order != nil"
  | where_exp: "item", "item.parent == nil"
  | where_exp: "item", "item.nav_exclude != true"
  | sort: "nav_order" %}

{% for section in main_pages %}

## [{{ section.title }}]({{ section.url | relative_url }})

{% assign children = site.pages
  | where: "parent", section.title
  | where_exp: "item", "item.nav_exclude != true"
  | sort: "nav_order" %}

{% for child in children %}

- [{{ child.title }}]({{ child.url | relative_url }})

{% assign grandchildren = site.pages
  | where: "parent", child.title
  | where: "grand_parent", section.title
  | where_exp: "item", "item.nav_exclude != true"
  | sort: "nav_order" %}

{% for grandchild in grandchildren %}
  - [{{ grandchild.title }}]({{ grandchild.url | relative_url }})
{% endfor %}

{% endfor %}

{% endfor %}

---

## Información adicional

Este mapa presenta las páginas públicas organizadas según la estructura editorial de Gato Munchkin.

Para los motores de búsqueda y otros sistemas de rastreo también está disponible el [mapa XML]({{ '/sitemap.xml' | relative_url }}), generado automáticamente por Jekyll.

El contenido del sitio se desarrolla mediante información científica, documentación institucional y observaciones identificadas según su nivel de evidencia.
