---
layout: rules-layout
title: rules
full-title: Rules of the Game
category: rules
description: "Rules of play for "
keywords: "rpg rules, "
permalink: /rules/
---

<ol>
  {% for section in site.categories.rules reversed %}
    <li>
      <a href="{{site.baseurl}}{{section.url}}">{{section.full-title}}</a>
    </li>
  {% endfor %}
</ol>

