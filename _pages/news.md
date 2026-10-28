---
layout: page
title: News
permalink: /news
---
{% assign news = site.news | sort: 'date' | reverse %}
{% for entry in news %}
<article class="media">
  <div class="media-content">
    <div class="content">
      <p><b>{{ entry.date | date_to_string }} — {{ entry.title }}</b></p>
      {{ entry.content }}
    </div>
  </div>
</article>
{% endfor %}
