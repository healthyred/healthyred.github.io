---
title:  "Blogs"
layout: archive
permalink: /Blogs/
author_profile: true
comments: true
header:
  overlay_image: /assets/images/back.jpg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  #{% include paginator.html %}
---

<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3>

[Resume](https://healthyred.github.io/assets/images/resume.pdf "an image title")

{% for post in paginator.posts %}
  {% include archive-single.html %}
{% endfor %}

