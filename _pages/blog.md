---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: false
header:
  overlay_color: "#00334e"
  overlay_image: /assets/images/mm-home-page-feature.jpg
  overlay_filter: "rgba(0, 51, 78, 0.72)"
---

{% assign entries_layout = page.entries_layout | default: 'list' %}
<div class="entries-{{ entries_layout }}">
  {% for post in site.posts %}
    {% include archive-single.html type=entries_layout %}
  {% endfor %}
</div>
