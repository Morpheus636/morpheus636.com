---
title: Contact
permalink: /contact
layout: page
exclude: true
---

<style>
    button{
        margin-left: 10%;
        width: 80%;
        margin-right: 10%;
        height: 40px;
        margin-bottom: 10px;
    }

    i{
        font-size: 20px;
        padding-right: 10px;
    }
</style>

# Socials
<hl />

{%- assign social = site.social_links -%}
{%- if social.twitter -%}
<button onclick="location.href='https://twitter.com/{{ social.twitter | cgi_escape | escape }}'" type="button">
<i class="ai-twitter-fill"></i>Twitter
</button>
{%- endif -%}

{%- if social.instagram -%}
<button onclick="location.href='https://instagram.com/{{ social.instagram | cgi_escape | escape }}'" type="button">
<i class="ai-instagram-fill"></i>Instagram
</button>
{%- endif -%}

{%- if social.github -%}
<button onclick="location.href='https://github.com/{{ social.github | cgi_escape | escape }}'" type="button">
<i class="ai-github-fill"></i> GitHub
</button>
{%- endif -%}

{%- if social.stackoverflow_id and social.stackoverflow_name -%}
<button onclick="location.href='https://stackoverflow.com/users/{{ social.stackoverflow_id | cgi_escape | escape }}/{{ social.stackoverflow_name | cgi_escape | escape }}'" type="button">
<i class="ai-stack-overflow-fill"></i> StackOverflow
</button>
{%- endif -%}

{%- if social.twitch -%}
<button onclick="location.href='https://twitch.tv/{{ social.twitch | cgi_escape | escape }}'" type="button">
<i class="ai-twitch-fill"></i>Twitch
</button>
{%- endif -%}

{%- if social.youtube_channel -%}
<button onclick="location.href='https://www.youtube.com/channel/{{ social.youtube_channel | cgi_escape | escape }}'" type="button">
<i class="ai-youtube-fill"></i>YouTube
</button>
{%- endif -%}

{%- if social.reddit -%}
<button onclick="location.href='https://reddit.com/u/{{ social.reddit | cgi_escape | escape }}'" type="button">
<i class="ai-reddit-fill"></i>Reddit
</button>
{%- endif -%}

{%- if social.buymeacoffee -%}
<button onclick="location.href='https://www.buymeacoffee.com/{{ social.buymeacoffee | cgi_escape | escape }}'" type="button">
<i class="ai-coffee"></i>Buy Me a Coffee
</button>
{%- endif -%}

{%- for mst in social.mastodon -%}
{%- if mst.username and mst.instance -%}
<button onclick="location.href='https://{{ mst.instance | cgi_escape | escape}}/@{{mst.username}}'" type="button">
Mastodon
</button>
{%- endif -%}
{%- endfor -%}

<hl />


# Contact Info

**Email:** [{{ site.email }}](mailto:{{ site.email }})
<br/>**Discord:** [{{ social.discord_user }}]({{ social.discord_link }})
<br/>**Phone:** {{ site.phone }}
