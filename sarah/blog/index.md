---
layout: blog
title:  "Blog"
---

# Sarah's Blog
<ul>
  {% for post in site.posts %}
    <li>
      {{ post.excerpt }} <a href="{{ post.url }}">Read More...</a>
    </li>
  {% endfor %}
</ul>
