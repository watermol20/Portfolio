---
layout: page
title: About
permalink: /about/
weight: 1
---

# **About Me**

Hi, I am **{{ site.author.name }}**,

Not only am I a goal-driven accounting student, I am a baker, gamer, photographer, tea enthusiast, and many more things. I thoroughly enjoy working in a team environment, but I thrive under pressure when working on my own as well. I am detail orientated and look into all possibilities when making a decision. I prefer to listen more than talk because I am enchanted with the thought of learning something new every day.

{% capture list_items %}
Applications
Compliances
Work Experience
Extracurricular Activities
{% endcapture %}
{% include elements/list.html title="Table of Contents" type="toc" %}

<div class="row">

  <div class="col-lg">
    <h2 id="applications">Applications</h2>
      {% for skill in site.data.applications %}
        <p>- {{ skill.name }}</p>
      {% endfor %}
  </div>

  <div class="col-lg">
    <h2 id="compliances">Compliances</h2>
      {% for skill in site.data.compliances %}
        <p>- {{ skill.name }}</p>
      {% endfor %}
  </div>

</div>

## Work Experience

<div class="row">
{% include about/timeline.html source=site.data.timeline-work %}
</div>

<br>

## Extracurricular Activities
<div class="row">
{% include about/timeline.html source=site.data.timeline-extracurricular %}
</div>
