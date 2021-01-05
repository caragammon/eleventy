---
tags: page
layout: main.njk
title: Blog
button: This is my blog page
buttonLink: http://google.com
---
# {{ title }}


<ul>
{%- for post in collections.post -%}
  <li>{{ post.data.title }}</li>
{%- endfor -%}
</ul>