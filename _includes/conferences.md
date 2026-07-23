## Conferences & Talks

<ul>
{% for talk in site.data.conferences.main %}
  <li>
    <strong>{{ talk.title }}</strong> — {{ talk.event }}, {{ talk.date }}
    {% if talk.presentation %} [<a href="{{ talk.presentation }}">Presentation</a>]{% endif %}
  </li>
{% endfor %}
</ul>
