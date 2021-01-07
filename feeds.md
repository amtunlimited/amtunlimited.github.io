---
layout: default
permalink: /feeds/
title: Home
---
Here's a list of my various online feeds. As always, you can [email me](mailto:aaron.tagliaboschi@gmail.com) and I would absolutely love to hear from you.

{%for feed in site.data.feeds%}
  [{{feed.name}}]({{feed.url}}) 
  : {{feed.desc}}
{%endfor%}
