---
layout: page
permalink: /projects/pyautomations
exclude: true
---
<style>
    button{
        height: 40px;
    }
</style>

# PyAutomations
PyAutomations is a framework for writing automations using python and hosting them in replit.

## Technologies
- Python 3
- Flask
- Schedule

<button onclick="location.href='https://github.com/morpheus636/PyAutomations'" type="button">View PyAutomations on GitHub</button>

### Blog posts about PyAutomations
  <div class="archive-group">
    {% for post in site.categories["PyAutomations"] %}
    <article class="archive-item">
      <h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
    </article>
    {% endfor %}
  </div>
  