---
title:  "RetroPie"
layout: default
categories: projects
---
Almost done with my RetroPie NES classic project. I'll start posting steps here shortly.

<ul class="post-list">
    {% for post in site.retropie reversed %}
        <li>
            <h2 class="post-link-container">
                <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
            </h2>
            <div class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</div>
            {{ post.excerpt }}
        </li>
    {% endfor %}
</ul>
