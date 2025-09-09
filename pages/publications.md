---
layout: single
title: "Publications"
permalink: /publications/
---

Here is a selection of my publications.  

{% include base_path %}

{% for pub in site.publications reversed %}
- **{{ pub.title }}**, {{ pub.venue }} ({{ pub.date | date: "%Y" }})  
  [PDF]({{ pub.paperurl }})  
{% endfor %}
