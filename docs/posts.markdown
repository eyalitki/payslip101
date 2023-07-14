---
layout: default
title: רשימת המאמרים
date: 2023-07-14 14:30:00 +0200
permalink: /post/
---

{% for post in site.posts %}
  <h2>{{ post.title }}</h2>
  <p>{{ post.description }} - 
    <a href="{{ post.url }}">לינק.</a>
  </p>
{% endfor %}

## דברי פתיחה
רקע לפתיחת הבלוג ולינק לטבלאות חישוב תלוש השכר מברוטו לנטו, מיסוי, תנאים סוציאליים ועוד - [לינק](/about).
