---
title: News
permalink: /news/
layout: archive
entries_layout: list
author_profile: false
---

{% assign news_posts = site.posts %}

{% if news_posts.size > 0 %}
  {% for post in news_posts %}
    {% include archive-single.html type="list" %}
  {% endfor %}
{% else %}
No news yet.
{% endif %}
