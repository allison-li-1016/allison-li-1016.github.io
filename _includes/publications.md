## Publications

<ul class="publication-list">
{% for pub in site.data.publications.main %}
  <li>
    <strong>{{ pub.title }}</strong><br>
    {{ pub.authors }}<br>
    <em>{{ pub.conference }}</em><br>
    {% if pub.pdf %}[<a href="{{ pub.pdf }}">PDF</a>]{% endif %}
    {% if pub.code %}[<a href="{{ pub.code }}">Code</a>]{% endif %}
    {% if pub.page %}[<a href="{{ pub.page }}">Project Page</a>]{% endif %}
    {% if pub.bibtex %}[<a href="{{ pub.bibtex }}">BibTeX</a>]{% endif %}
  </li>
{% endfor %}
</ul>
