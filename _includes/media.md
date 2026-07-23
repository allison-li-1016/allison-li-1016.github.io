## Media & Press

<ul>
{% for item in site.data.media.main %}
  <li><a href="{{ item.link }}">{{ item.title }}</a> — {{ item.outlet }}, {{ item.date }}</li>
{% endfor %}
</ul>
