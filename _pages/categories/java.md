---
titel: "JAVA"
layout: archive
permalink: categories/java
author_profile: true
types: posts
---

{% assign posts = site.categories.categories %}
{% for post in posts %}
{% include archive-single.html type=page.entries_layout %}
{% endfor %}
