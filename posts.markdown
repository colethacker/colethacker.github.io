---
layout: page
title: Posts
permalink: /posts/
---
{% assign sorted_categories = site.categories | sort %}
{% for category in sorted_categories %}
  <h2>{{ category[0] | capitalize }}</h2>
  <ul>
    {% assign posts_in_category = category[1] | sort: "date" | reverse %}
    {% for post in posts_in_category %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        <span> - {{ post.date | date: "%B %d, %Y" }}</span>
      </li>
    {% endfor %}
  </ul>
{% endfor %}