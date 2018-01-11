---
layout: post
title: "Playlist: Januari 2018"
excerpt: "Lagu-lagu yang saya putar di Bulan Januari 2018 ini."
categories: collections
tags: [playlist]
image:
  feature: 
  thumb: playlist/2018januari.jpg
  credit:  
  creditlink: 
comments: false
share: true
---
<figure>
  <img src="/images/playlist/2018januari.jpg" alt="image">
</figure>

<a class="btn" href="https://itunes.apple.com/id/playlist/2018-january/pl.u-AkAmVobtjEZKex">Preview Lagu di Apple Music</a>

<ul class="post-list">
{% for musik in site.data.januaridelapanbelas %}
  <li><article><a href="{{ musik.url }}">{{ musik.song }} <span class="entry-date"><time>{{ musik.time }}</time></span><span class="excerpt">{{ musik.artist }}</span></a></article></li>
{% endfor %}
</ul>