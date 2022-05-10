---
layout: page
permalink: /projects/redownload
exclude: true
title: Redownload
description: |
  A tool for downloading audio files from Relisten
---
<style>
    button{
        height: 40px;
    }
</style>

# Redownload
Redownload is a utility for downloading audio files from [Relisten](https://relisten.com), a streaming service for concert recordings. The user can provide Redownload with a link to a track on Relisten, and Redownload will find the source of the file and download it to a specified location.

## Technologies
- Python 3
- Argparse
- BeautifulSoup 4
- Requests

<button onclick="location.href='https://github.com/morpheus636/redownload'" type="button">View Redownload on GitHub</button>

### Blog posts about Redownload
  <div class="archive-group">
    {% for post in site.categories["Redownload"] %}
    <article class="archive-item">
      <h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
    </article>
    {% endfor %}
  </div>