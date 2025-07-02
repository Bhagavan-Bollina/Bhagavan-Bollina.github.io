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
## Medium Articles

<ul>
  <li>
    <a href="https://medium.com/@yourusername/how-i-exploited-app-runner-to-gain-shell-access-abc123" target="_blank">
      How I Exploited App Runner to Gain Shell Access
    </a> — Published on Medium
  </li>
  <li>
    <a href="https://medium.com/@yourusername/flying-under-the-radar-with-aws-iam-part-1-xyz456" target="_blank">
      Flying Under the Radar with AWS IAM – Part 1
    </a> — Published on Medium
  </li>
</ul>

<!-- Gap Section -->
<div style="height: 40px;"></div>
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
