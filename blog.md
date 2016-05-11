---
layout: blog-layout
title: blog
full-title: Development Blog
category: blog
description: "Game developer's blog for "
keywords: "game development, tabletop game development, rpg game development, "
---

<ul>
  {% for post in site.categories.blog_posts %}
    <li>
      <p>
        <a href="{{site.baseurl}}{{post.url}}">{{post.full-title}}</a> &bull; {{ post.date | date: '%B %d, %Y' }}
      <p>
    </li>
  {% endfor %}
</ul>