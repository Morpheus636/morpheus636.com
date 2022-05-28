---
layout: page
permalink: /projects/pyautomations
exclude: true
title: PyAutomations
description: |
  A framework for automatically running python scripts hosted in replit.
---
<style>
    button{
        height: 40px;
    }
</style>

PyAutomations is a framework for writing automations using Python and hosting them in Replit.

The main goal of PyAutomations is to create an internet-connected automation scripting environment
to do the same types of things as IFTTT (which is to say, nearly anythng), but using Python instead
of drag-and-drop, offering users near-infinite freedom. Unlike IFTTT, it also allows users to 
version-control their automations using Git, something that is useful to power users, and incredibly
familiar to experienced developers.

PyAutomations is designed to be run in Replit, as a simple, free hosting option, but it can also be easily
adapted to self host for a completely independent solution.

The framework itself currently features two types of automation triggers, but as an open-source 
project, you can of course add your own if there are more you need: 
- Schedule
  - PyAutomations uses the `schedule` PyPi package to let you schedule automations to run, either on
    an interval or at dedicated times. For UN*X users, this is the PyAutomations equivilent to a cron job.
- Webhook
  - PyAutomations provides an simple interface for Flask to allow users to easily configure API endpoints
    which trigger automations. Using PyAutomations to trigger automations from a webhook requires no knowledge
    of Flask, and you won't even need to touch Flask code directly to use it as a trigger; PyAutomations
    handles it for you. 


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
  