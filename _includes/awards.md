## Awards & Honors

<ul>
{% for award in site.data.awards.main %}
  <li><strong>{{ award.year }}</strong> — {{ award.name }}{% if award.org %}, {{ award.org }}{% endif %}</li>
{% endfor %}
</ul>
