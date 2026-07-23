## Highlighted Research Projects

<div class="project-grid">
{% for project in site.projects %}
  <a class="project-card" href="{{ project.url | relative_url }}">
    <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
    <h4>{{ project.title }}</h4>
    <p>{{ project.summary }}</p>
  </a>
{% endfor %}
</div>
