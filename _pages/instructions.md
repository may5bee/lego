---
layout: page
title: instructions
permalink: /instructions/
---

<div class="content-section">

<ul class="post-list">
    {% for instruction in site.instructions %}
      <li> 
        <a class="post-link" href="{{ instruction.url | prepend: site.baseurl }}"><img class="instructions-img" src="" alt="instruction.alt" width="80" height="80"></a>
        <div class="instructions-body">
        <h4>
          <a class="post-link" href="{{ instruction.url | prepend: site.baseurl }}">{{ instruction.title }}</a>
        </h4>
        <!-- <a href="{{ instruction.url | prepend: site.baseurl }}">Download</a>
        <a href="{{instruction.link}}">More Information</a> -->
    	</div>
      </li>
    {% endfor %}
</ul>
</div>