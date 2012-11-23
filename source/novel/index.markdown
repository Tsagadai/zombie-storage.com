---
layout: custom_page
title: "Untitled"
author: "Christoph Curran"
date: 2012-11-02 13:53
comments: true
sharing: true
footer: true
---

<ul class="posts">
Written by {{ page.author }}
{% for post in site.categories.nanowrimo %}
  <section>
    <h2>{{ post.title }}</h2>
    {{ post.content}}
    <hr/>
  </section>
{% endfor %}
</ul>

