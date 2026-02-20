---
layout: post
title: "North and Hillard"
categories: [latin, nh]
tags: [nh, latin]
---

M.A. North and A.E. Hillard's *Latin Prose Composition* is a compendium of brief lessons on the fundamentals of composition. It is available at [Archive Online](https://archive.org/details/north-m.-hilladr-a.-latin-prose-composition-1913/mode/2up).

I am working through the lessons, and self-correcting them, here:

<ul>
  {% for post in site.tags.nh %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>

#latin #nh 