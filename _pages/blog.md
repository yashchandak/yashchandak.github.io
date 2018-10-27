---
permalink: "/blog/"
layout: page
title: Blog
sidebar_link: false
---

<div class="content">
  {{ content }}

  {% for post in paginator.posts %}
  <article class="post-body">
    <h2 class="post-title">
      <a href="{{ site.baseurl }}{{ post.url }}">
        {{ post.title }}
      </a>
    </h2>
    {% include post-meta.html post=post %}

    {{ post.content }}

  </article>
  {% endfor %}
</div>