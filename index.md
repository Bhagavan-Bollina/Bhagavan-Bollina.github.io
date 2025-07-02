---
layout: default
title: Home
---

I’m Bhagavan Bollina, aka 0xcriminal, a hacker and security aficionado!

## Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%b %-d, %Y" }}
    </li>
  {% endfor %}
</ul>
