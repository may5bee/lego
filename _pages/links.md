---
layout: page
title: 
permalink: /links/
---

<div class="content-section">
<ul class="post-list">
    {% for link in site.links %}
      <li> 
        <h2>
          <a class="post-link" href="{{ link.link }}">{{link.title}}</a>
        </h2>
        <p>{{link.description}}</p>
      </li>
    {% endfor %}
</ul>
</div>