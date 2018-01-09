---
layout: page
title: Notes
excerpt: "An archive of notes posts sorted by date."
search_omit: true
---

<ul class="post-list">
{% for post in site.categories.notes %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>