---
layout: page
title: Archives
excerpt: "Arsip semua tulisan saya"
search_omit: true
---

<p>Ini adalah halaman yang memuat arsip semua tulisan saya.</p>

<h3>Notes</h3>
<ul class="post-list">
{% for post in site.categories.blog %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>
