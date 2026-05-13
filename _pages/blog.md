---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: false
header:
  overlay_color: "#00334e"
---

{% assign entries_layout = page.entries_layout | default: 'list' %}
<div class="entries-{{ entries_layout }}">
  {% for post in site.posts %}
    {% include archive-single.html type=entries_layout %}
  {% endfor %}
</div>
