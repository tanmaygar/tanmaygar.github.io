---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

## Areas of Interest
My academic interest is at the intersection of Machine Learning and Computer Vision. Over time, I've explored the various aspects of this domain, using the latest tools and frameworks. Whether it's traditional image processing techniques or advanced deep learning methodologies, I'm always on the lookout for the next challenge in computer vision. Feel free to explore my work and reach out for collaborations or discussions!

## Publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

### Recent News
My paper on <i>Advancing Ante Hoc Explainable Models through Generative Adversarial Networks</i> has been accepted at AAAI 2024 Conference Workshop - 12th December 2023 (To be updated soon)