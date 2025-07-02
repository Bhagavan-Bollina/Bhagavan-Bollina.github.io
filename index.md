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
    <strong>Talk: How to be Safe on the Internet</strong> — Delivered at [Girlscript Ireland](#) 
  </li>
  <li>
    <strong>Talk: Flying Under Radar - AWS IAM 1</strong> — Delivered at [Null Hyderabad Chapter 2022](#)
  </li>
  <li>
    <strong>Talk: Flying Under Radar - AWS IAM 2</strong> — Delivered at [Null Hyderabad Chapter 2022](#)
  </li>
  <li>
    <strong>Talk: Mind the Gap: Identifying and Addressing Weaknesses in Your GCP</strong> — Delivered at [Null Hyderabad Chapter 2023](#)
  </li>
  <li>
    <strong>Trainer: Breaking & Pwning Servers and Applications in AWS & GCP</strong> — Delivered at [Nullcon 2022](#)
  </li>
  <li>
    <strong>Speaker: Getting Shell and Data Access in AWS App Runner - A Journey from Initial Foothold to Compromising the AWS Infra</strong> — Delivered at [Bsides CDMX 2023](#)
  </li>
  <li>
    <strong>Trainer: Breaking & Pwning Servers and Applications in AWS & GCP</strong> — Delivered at [Bsides Bangalore 2023](#)
  </li>
</ul>
