---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<ul>
  {% for post in site.posts %}
    <li>
      <h2>{{ post.title }}</h2>
      <h3>{{ post.date| date: "%m-%d-%Y %H:%M" }}</h3>
      <p>{{ post.content }}</p>
      <hr>
    </li>
  {% endfor %}
</ul>