---
layout: default
permalink: /blog/
title: Posts
---

{% for post in site.posts %}
# [{{ post.title }}]({{ post.url }})
<div class="author">
  by {{ post.author | default: site.author }} <br />
  {{ post.date | date: "%-d %B %Y" }}
</div>

{{post.excerpt}}

---
{% endfor %}
