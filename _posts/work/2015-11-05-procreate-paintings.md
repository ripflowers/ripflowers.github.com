---
layout: archive
permalink: /procreate-paintings/
title: "Procreate Paintings"
excerpt: &excerpt "Gallery of portraits digitally painted with [Procreate](http://procreate.si/) on an iPad."
subtitle: *excerpt
modified: 2015-11-30T13:04:35-05:00
image: 
  teaser: procreate-paintings-teaser.jpg
  thumb: procreate-paintings-150.jpg
tags: [Procreate, painting, drawing, portrait, illustration]
fullwidth: true
featured: 
ads: false
work: "Illustration"
---

<ul class="th-grid">
{% for post in site.categories.procreate-paintings %}
  <li style="width: 200px;">
    <a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}">
      <img class="load" src="{{ site.url }}/images/preload-150.png" data-original="{{ site.url }}/images/{{ post.image.thumb }}" alt="">
      <noscript><img src="{{ site.url }}/images/{{ post.image.thumb }}" alt=""></noscript>
    </a>
  </li>
{% endfor %}
</ul>
