---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<ul>
  {% for post in site.posts %}
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    {{ post.date }}
    {{ post.excerpt }}
  {% endfor %}
</ul>