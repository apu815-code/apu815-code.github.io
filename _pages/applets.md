---
layout: page
permalink: /applets/
title: applets
description: Interactive tools and visualizations from my research and teaching. Run them right in your browser.
nav: true
nav_order: 4
---

{% assign applets_sorted = site.applets | sort: "importance" %}

{% if applets_sorted.size == 0 %}
<p>No applets published yet.</p>
{% else %}
<div class="row row-cols-1 row-cols-md-3">
  {% for applet in applets_sorted %}
  <div class="col">
    <a href="{{ applet.url | relative_url }}">
      <div class="card h-100 hoverable">
        {% if applet.img %}
          {% include figure.liquid loading="eager" path=applet.img sizes="250px" alt="applet preview" class="card-img-top" %}
        {% endif %}
        <div class="card-body">
          <h2 class="card-title">{{ applet.title }}</h2>
          <p class="card-text">{{ applet.description }}</p>
          {% for tag in applet.tags %}
            <span class="card-tag t{{ forloop.index | modulo: 4 | plus: 1 }}">{{ tag }}</span>
          {% endfor %}
        </div>
      </div>
    </a>
  </div>
  {% endfor %}
</div>
{% endif %}

<hr>

<p class="text-muted"><em>All applets run entirely in your browser; nothing you enter is sent anywhere.</em></p>
