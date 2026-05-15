---
layout: default
---

I taught math and computer science in NYC public schools for a decade — founding a school, piloting a national CS curriculum, arguing about algebra, and building the spreadsheet systems that held everything together when the world went sideways in 2020.

Then I went home to raise my third kid. Five years later, I'm building again.

I learn slowly and deeply. I do my best work from a foundation I trust. This is the workshop.

## On the Bench

<div class="projects">
  {% for project in site.data.projects %}
  <div class="project">
    <h3><a href="{{ project.url }}">{{ project.name }}</a></h3>
    <p>{{ project.description }}</p>
    {% if project.pypi or project.docs %}
    <p>
      {% if project.pypi %}
      <a href="{{ project.pypi }}">PyPI</a>
      {% endif %}
      {% if project.docs %}
      <a href="{{ project.docs }}">Docs</a>
      {% endif %}
    </p>
    {% endif %}
  </div>
  {% endfor %}
</div>

<div class="closing">
<p>Based in the Hudson Valley. Three kids. Still consulting for a <a href="https://www.vizcarraguitars.com/">guitar maker in Santa Fe</a> on shop data systems, which is a sentence that somehow makes sense if you know the path.</p>
<p>Looking for work where teaching, data, and systems thinking meet. <a href="mailto:ericallatta@gmail.com">Say hello</a>.</p>
</div>