---
layout: default
title: Mr. Allatta's landing page
---

<h1>Welcome to the landing page for Mr. Allatta's github websites.</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
