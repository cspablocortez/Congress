---
layout: default
---

<ul class="blog-posts">
    {% for post in site.posts %}
    <li>
        <span class="post-date">{{ post.date | date: "%A %-d %b %Y" }}</span><a href="{{ post.url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
</ul>
