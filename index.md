---
layout: default
---


<h2> Stories: </h2>
<ul>
{% for story in site.stories %}
  <li>
    <a href="{{ story.url }}">
      {{ story.title }}
    </a>
  </li>
{% endfor %}
</ul>
