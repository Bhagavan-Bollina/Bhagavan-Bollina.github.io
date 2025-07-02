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
<!-- Gap Section -->
<div style="height: 40px;"></div> <!-- This adds space between sections -->

## My Talks
Here are some of the talks I've delivered:
<!-- Gap Section -->
<div style="height: 40px;"></div> <!-- This adds space between sections -->

<ul>
  <li>
    <strong>Talk Title 1</strong> — Delivered at [Event Name](#) on [Date]
    <p>Description of the talk and key takeaways. You can include a link to the video or slides here as well.</p>
  </li>
  <li>
    <strong>Talk Title 2</strong> — Delivered at [Event Name](#) on [Date]
    <p>Description of the talk and key takeaways.</p>
  </li>
  <li>
    <strong>Talk Title 3</strong> — Delivered at [Event Name](#) on [Date]
    <p>Description of the talk and key takeaways.</p>
  </li>
</ul>
