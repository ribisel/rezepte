# Welcome

<ul>
  {% for gericht in site.hauptgerichte %}
    <li>
      <a href="{{ gericht.url }}">{{ gericht.content }}</a>
    </li>
  {% endfor %}
</ul>
