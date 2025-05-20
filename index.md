---
layout: home
title: Rahul’s Thinking Ground
---

_Exploring strategy, analytics, transformation, and all things that move markets and minds._

---

Welcome to my curated collection of writing, frameworks, and reflections — drawn from the front lines of business transformation, data-driven strategy, and AI disruption.

---

## Latest Posts

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
{{ post.excerpt }}

---
{% endfor %}
