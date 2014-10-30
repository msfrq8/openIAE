---
published: true
layout: nav_dev_resources

---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/iae-global/{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
