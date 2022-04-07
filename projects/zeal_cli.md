---
layout: page
permalink: /projects/zeal-cli
exclude: true
---
<style>
    button{
        height: 40px;
    }
</style>

# Zeal CLI
Zeal-CLI is a command-line-interface for managing [Zeal](https://zealdocs.org/) docsets on Linux. It's syntax is roughly based on the basic syntax of the `apt` package manager, because Zeal CLI is basically a package manager for docsets.


## Technologies
- Python 3
- Argparse
- BeautifulSoup 4
- Requests
- PyYAML


## Credits
Just like Zeal, Zeal-CLI sources docsets from [Dash](https://kapeli.com/dash). Special thanks to Dash's developer, [Kapeli](https://github.com/Kapeli) for granting me permission to use their docsets.


<button onclick="location.href='https://github.com/morpheus636/zeal-cli'" type="button">View Zeal CLI on GitHub</button>


### Blog posts about Zeal CLI
  <div class="archive-group">
    {% for post in site.categories["Zeal-CLI"] %}
    <article class="archive-item">
      <h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
    </article>
    {% endfor %}
  </div>