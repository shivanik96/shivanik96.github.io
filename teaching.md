---
layout: page
permalink: /teaching/
title: Teaching
---

{:.lead}
## Invited Talks

<div class="post-list">
  {% for post in site.posts %}
    {% if post.type == "talk" %}
      {% assign currentdate = post.date | date: "%Y" %}
      {% if currentdate != date %}
        <h2 id="y{{ currentdate }}" class="year">{{ currentdate }}</h2>
        {% assign date = currentdate %}
      {% endif %}

      <div class="post-block">
        {% if post.venue %}<span style="float: right; font-size: 0.95em; color: #888;">{{ post.venue }}</span>{% endif %}
        <h3>
          {{ post.title }}
        </h3>
        <span class="post-meta" title="{{ post.date | date: "%b %-d Y" }}">{{ post.date | date: "%b" }} <span class="meta-year">{{ currentdate }}</span></span>
        {% if post.description %}<p class="post-subtitle">{{ post.description }}</p>{% endif %}
      </div>
    {% endif %}
  {% endfor %}
</div>

{:.lead}

{:.lead}
## Guest Lectures

<div class="post-list">
  {% for post in site.posts %}
    {% if post.type == "lecture" %}
      {% assign currentdate = post.date | date: "%Y" %}
      {% if currentdate != date %}
        <h2 id="y{{ currentdate }}" class="year">{{ currentdate }}</h2>
        {% assign date = currentdate %}
      {% endif %}

      <div class="post-block">
        {% if post.venue %}<span style="float: right; font-size: 0.95em; color: #888;">{{ post.venue }}</span>{% endif %}
        <h3>
          {{ post.title }}
        </h3>
        <span class="post-meta" title="{{ post.date | date: "%b %-d Y" }}">{{ post.date | date: "%b" }} <span class="meta-year">{{ currentdate }}</span></span>
        {% if post.description %}<p class="post-subtitle">{{ post.description }}</p>{% endif %}
      </div>
    {% endif %}
  {% endfor %}
</div>

{:.lead}
## Teaching Assistant

<div class="post-list">
  {% for post in site.posts %}
    {% if post.type == "teaching" %}
      {% assign currentdate = post.date | date: "%Y" %}
      {% if currentdate != date %}
        <h2 id="y{{ currentdate }}" class="year">{{ currentdate }}</h2>
        {% assign date = currentdate %}
      {% endif %}

      <div class="post-block">
        {% if post.venue %}<span style="float: right; font-size: 0.95em; color: #888;">{{ post.venue }}</span>{% endif %}
        <h3>
          {{ post.title }}
        </h3>
        <span class="post-meta" title="{{ post.date | date: "%b %-d Y" }}">{{ post.date | date: "%b" }} <span class="meta-year">{{ currentdate }}</span></span>
        {% if post.description %}<p class="post-subtitle">{{ post.description }}</p>{% endif %}
      </div>
    {% endif %}
  {% endfor %}
</div>