---
title: News
nav:
  order: 5
  tooltip: Latest events
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}News

A place to find out about new publications, conferences attended etc...

{% include section.html %}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}
