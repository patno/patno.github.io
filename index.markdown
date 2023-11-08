---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: post
---

{% for post in site.posts %}
  <article>
    <h1>
      <a href="{{ post.url }}">
      </a>
    </h1>
    {{ post.content }}
  </article>
{% endfor %}