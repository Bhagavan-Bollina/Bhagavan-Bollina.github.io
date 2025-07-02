---
layout: default
title: Home
---

I’m Bhagavan Bollina, aka 0xcriminal, a hacker and security aficionado!

## Latest Posts

<ul style="margin-bottom: 40px;">
  {% for post in site.posts %}
    <li style="margin-bottom: 10px;">
      <a href="{{ post.url }}" style="font-weight: bold; color: #0077cc; text-decoration: none;">{{ post.title }}</a> — 
      <span style="font-size: 0.9em; color: #555;">{{ post.date | date: "%b %-d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>

<!-- Gap Section -->
<div style="height: 40px;"></div> <!-- Adds space between sections -->

## Medium Articles

<div style="margin-bottom: 30px;">
  <ul style="list-style-type: none; padding-left: 0;">
    {% for article in site.medium_articles %}
      <li style="margin-bottom: 15px;">
        <a href="{{ article.url }}" target="_blank" style="font-weight: bold; color: #0077cc; text-decoration: none;">{{ article.title }}</a>
        <br>
        <span style="font-size: 0.9em; color: #555;">Published on {{ article.source }}</span>
      </li>
    {% endfor %}
  </ul>
</div>

<!-- Gap Section -->
<div style="height: 40px;"></div>

## My Talks

Here are some of the talks I've delivered:

<div style="margin-bottom: 30px;">
  <ul style="list-style-type: none; padding-left: 0;">
    <li style="margin-bottom: 15px;">
      <strong>Talk: How to be Safe on the Internet</strong> — Delivered at [Girlscript Ireland](#)
    </li>
    <li style="margin-bottom: 15px;">
      <strong>Talk: Flying Under Radar - AWS IAM 1</strong> — Delivered at [Null Hyderabad Chapter 2022](#)
    </li>
    <li style="margin-bottom: 15px;">
      <strong>Talk: Flying Under Radar - AWS IAM 2</strong> — Delivered at [Null Hyderabad Chapter 2022](#)
    </li>
    <li style="margin-bottom: 15px;">
      <strong>Talk: Mind the Gap: Identifying and Addressing Weaknesses in Your GCP</strong> — Delivered at [Null Hyderabad Chapter 2023](#)
    </li>
    <li style="margin-bottom: 15px;">
      <strong>Trainer: Breaking & Pwning Servers and Applications in AWS & GCP</strong> — Delivered at [Nullcon 2022](#)
    </li>
    <li style="margin-bottom: 15px;">
      <strong>Speaker: Getting Shell and Data Access in AWS App Runner - A Journey from Initial Foothold to Compromising the AWS Infra</strong> — Delivered at [Bsides CDMX 2023](#)
    </li>
    <li style="margin-bottom: 15px;">
      <strong>Trainer: Breaking & Pwning Servers and Applications in AWS & GCP</strong> — Delivered at [Bsides Bangalore 2023](#)
    </li>
  </ul>
</div>

<!-- Gap Section -->
<div style="height: 40px;"></div>
