---
title: Publications
layout: gridlay
excerpt: Publications.
sitemap: false
permalink: "/publications/"
---

# Publications
### 2024
{% for publi in site.data.publist_24 %}

 {{ publi.authors }}: {{ publi.title }}, {{ publi.journal }}, {{ publi.status }}, {{ publi.year }}. [<a href="{{ publi.link }}">Link</a>]

{% endfor %}

### 2023
{% for publi in site.data.publist_23 %}

  {{ publi.authors }}: {{ publi.title }}, {{ publi.journal }}, {{ publi.status }}, {{ publi.year }}. [<a href="{{ publi.link }}">Link</a>]

{% endfor %}

### 2022
{% for publi in site.data.publist_22 %}

  {{ publi.authors }}: {{ publi.title }}, {{ publi.journal }}, {{ publi.status }}, {{ publi.year }}. [<a href="{{ publi.link }}">Link</a>]

{% endfor %}

### 2021
{% for publi in site.data.publist_21 %}

  {{ publi.authors }}: {{ publi.title }}, {{ publi.journal }}, {{ publi.status }}, {{ publi.year }}. [<a href="{{ publi.link }}">Link</a>] 

{% endfor %}

### 2020
{% for publi in site.data.publist_20 %}

  {{ publi.authors }}: {{ publi.title }}, {{ publi.journal }}, {{ publi.status }}, {{ publi.year }}. [<a href="{{ publi.link }}">Link</a>]
  
{% endfor %}
### 2019 and before
{% for publi in site.data.publist_19 %}

  {{ publi.authors }}: {{ publi.title }}, {{ publi.journal }}, {{ publi.status }}, {{ publi.year }}. [<a href="{{ publi.link }}">Link</a>]

{% endfor %}

{% for publi in site.data.publist_0 %}

  {{ publi.authors }}: {{ publi.title }}, {{ publi.journal }}, {{ publi.status }}, {{ publi.year }}. [<a href="{{ publi.link }}">Link</a>]

{% endfor %}
