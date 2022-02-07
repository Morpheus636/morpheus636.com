---
layout: page
permalink: /projects/desktop-scripts
exclude: true
---
<style>
    button{
        height: 40px;
    }
</style>

# Desktop Scripts
My desktop scripts consist of 2 github repositories that serve different purposes. Neither of them are intended for public use, since they're written specifically for my needs (and are frankly under-documented) but I have them published as open-source in case someone else has a use or wants to fork and modify them for their own purposes.
- `desktop_utils` is a set of BASH scripts and an installer which I wrote to solve problemts I have regularly in my day-to-day linux use. 

- `desktop_config` is a set of BASH scripts which I've written to make configuring my workstation simple, by running one script, it will install all my regularly used software, and update various settings and config files to exactly what I expect. It also serves the purpose of keeping my config in sync between all my devices.

<button onclick="location.href='https://github.com/morpheus636/desktop_utils" type="button">View desktop_utils on GitHub</button>
<button onclick="location.href='https://github.com/morpheus636/desktop_config" type="button">View desktop_config on GitHub</button>

### Blog posts about my Desktop Scripts
  <div class="archive-group">
    {% for post in site.categories["Desktop Scripts"] %}
    <article class="archive-item">
      <h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
    </article>
    {% endfor %}
  </div>
