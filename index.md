---
layout: default
path: /
---

# Posts

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})

{{post.excerpt}}

[More]({{ post.url }})
{% endfor %}

testing