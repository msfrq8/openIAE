---
published: true
layout: dev_resources
navigation: blog
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/iae-global/{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
