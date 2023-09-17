---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Areas of Interest
My academic journey has been largely driven by an interest in computer vision. Over time, I've delved into various aspects of this fascinating domain, using tools and frameworks that are at the forefront of the field. Whether it's traditional image processing techniques or advanced deep learning methodologies, I'm always on the lookout for the next challenge in computer vision. Feel free to explore my work and reach out for collaborations or discussions!

## Publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
