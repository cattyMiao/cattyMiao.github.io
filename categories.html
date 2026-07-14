---
layout: default
title: 分类
permalink: /categories
---

<a href="{{ "/" | relative_url }}" class="back-link" aria-label="Go back">
  <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
    <polyline points="15 18 9 12 15 6"></polyline>
  </svg>
</a>

<h1>分类</h1>

{% assign categories = site.posts | map: "category" | uniq | sort %}

<div class="tag-cloud">
  {% for category in categories %}
    {% assign count = site.posts | where: "category", category | size %}
    <a href="#{{ category | slugify }}" class="tag tag-cloud-item" data-count="{{ count }}" style="font-size: {{ count | times: 0.05 | plus: 0.78 }}rem;">
      {{ category }}<span class="tag-count">{{ count }}</span>
    </a>
  {% endfor %}
</div>

{% for category in categories %}
  {% assign posts = site.posts | where: "category", category %}
  <section class="tag-section">
    <h2 id="{{ category | slugify }}" class="tag-section-title">
      {{ category }}
      <span class="tag-section-count">{{ posts.size }} 篇</span>
    </h2>
    <ul>
      {% for post in posts %}
        <li class="post-list-item">
          <span class="home-date">{{ post.date | date: site.theme_config.date_format }}&raquo;</span>
          <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        </li>
      {% endfor %}
    </ul>
  </section>
{% endfor %}
