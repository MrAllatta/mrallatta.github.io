---
layout: default
title: My Jekyll Site
---

<h1>Welcome to My Jekyll Site</h1>
<p>This is a simple Jekyll homepage.</p>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
