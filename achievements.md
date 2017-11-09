---
layout: page
permalink: /achievements
---

<ul>
{% for achievement in site.data.achievements %}
  <li>
      {{ achievement.title }}
  </li>
{% endfor %}
</ul>
