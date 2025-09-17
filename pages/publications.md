---
layout: single
title: Publications
permalink: /publications/
---

{% for pub in site.publications reversed %}
- **{{ pub.title }}**, {{ pub.venue }} ({{ pub.date | date: "%Y" }})  
  {% if pub.paperurl %}[PDF]({{ pub.paperurl }}){% endif %}
{% endfor %}
