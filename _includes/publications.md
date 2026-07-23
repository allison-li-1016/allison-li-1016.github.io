## Publications

An asterisk * denotes that the authors contributed equally to the work.

<div class="publication-list">
{% for pub in site.data.publications.main %}
  <div class="publication-row">
    <div class="publication-title">{{ pub.title }}</div>
    <div class="publication-authors">{{ pub.authors }}</div>
    <div class="publication-meta">
      <em>{{ pub.conference }}</em>
      {% if pub.pdf %}[<a href="{{ pub.pdf }}">PDF</a>]{% endif %}
      {% if pub.preprint %}[<a href="{{ pub.preprint }}">Preprint</a>]{% endif %}
      {% if pub.code %}[<a href="{{ pub.code }}">Code</a>]{% endif %}
      {% if pub.page %}[<a href="{{ pub.page }}">Project Page</a>]{% endif %}
      {% if pub.bibtex %}[<a href="{{ pub.bibtex }}">BibTeX</a>]{% endif %}
    </div>
  </div>
{% endfor %}
</div>
