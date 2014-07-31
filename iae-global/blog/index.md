---
published: true
layout: default

---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/iae-global/iae-global/{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>