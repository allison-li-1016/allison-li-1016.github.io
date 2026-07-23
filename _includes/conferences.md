## Conferences & Talks

<ul>
{% for talk in site.data.conferences.main %}
  <li>
    <strong>{{ talk.title }}</strong> — {{ talk.event }}, {{ talk.date }}
    {% if talk.link %} [<a href="{{ talk.link }}">Link</a>]{% endif %}
  </li>
{% endfor %}
</ul>
