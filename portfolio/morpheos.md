---
layout: page
permalink: /portfolio/morpheos
exclude: true
title: MorpheOS
description: |
  A work-in-progress simple operating system developed for the purpose of learning low-level programming.
---
<style>
    button{
        height: 40px;
    }
</style>

MorpheOS is a simple operating system developed for the purpose of learning 
low-level programming. It is still very much a work-in-progress.


## Technologies
- x86 ASM
- C++

<button onclick="location.href='https://github.com/morpheus636/morpheOS'" type="button">View Zeal CLI on GitHub</button>


### Blog posts about MorpheOS
  <div class="archive-group">
    {% for post in site.categories["MorpheOS"] %}
    <article class="archive-item">
      <h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
    </article>
    {% endfor %}
  </div>
