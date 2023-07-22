
---

<strong>🆕 最近创建：</strong>
<ul>
  {% assign recent_notes = site.notes | sort: "date" | reverse %}
  {% for note in recent_notes | limit: 6 %}
    <li>
      {{ note['date']}} — <a class="internal-link" href="{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>


<strong>⏰ 最近更新：</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "date" | reverse %}
  {% for note in recent_notes | limit: 6 %}
    <li>
      {{ note['date']}} — <a class="internal-link" href="{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>
