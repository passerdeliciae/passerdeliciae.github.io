---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<h1>Latest posts</h1>
<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url | relative_url }}">
        {{ post.title }}
      </a>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>

<h1>Collections</h1>
<ul>
  <li><a href="{{ 'topics/latin/' | relative_url }}">Latin</a> ({{ site.categories.latin | size }})</li>
</ul>