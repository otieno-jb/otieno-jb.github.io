---
layout: page
title: Lab challenges
icon: fas fa-flag
order: 7
---

Write-ups of labs and CTF challenges I have completed. Each one covers the problem statement, my approach, the tools I used, screenshots and the lessons I took away.

{% assign labs = site.categories["Lab Challenges"] %}
{% if labs %}
<ul>
{% for post in labs %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> ({{ post.date | date: "%-d %b %Y" }})</li>
{% endfor %}
</ul>
{% else %}
<p>No write-ups yet.</p>
{% endif %}
