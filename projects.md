---
layout: project
title: Projects
permalink: /projects/
---

  <ul class="posts fa-ul">
    {% for post in paginator.posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>