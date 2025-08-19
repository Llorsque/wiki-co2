---
layout: default
title: Start
---

<section class="hero">
  <h1>Productenmatrix</h1>
  <p>Vind snel interne informatie over producten en diensten voor clubondersteuning. Gebruik de zoekbalk of kies een thema.</p>
  <div class="search-wrap">
    <input id="globalSearch" type="search" placeholder="Zoek op naam, thema, type of tags…">
  </div>
</section>

<div id="globalResults" class="grid" style="margin-top:12px"></div>

<hr>

### Thema’s (snelkoppelingen)
<div class="theme-grid">
  {% assign ts = site.themas | sort: 'title' %}
  {% for t in ts limit:8 %}
    <a class="btn-theme" href="{{ t.url | relative_url }}">{{ t.title }}</a>
  {% endfor %}
</div>

<details style="margin-top:10px">
  <summary>Alle thema’s</summary>
  <ul>
    {% assign ts = site.themas | sort: 'title' %}
    {% for t in ts %}
      <li><a href="{{ t.url | relative_url }}">{{ t.title }}</a></li>
    {% endfor %}
  </ul>
</details>
