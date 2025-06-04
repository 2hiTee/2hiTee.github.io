---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

L3D: Enhancing 2D Talking Portraits Synthesis Learning with Pitch information using 3D Blendshapes Priors \
**Yanming Yang**, Wenhao Rao, Ifat Yasin* (* denotes corresponding author)

Deformable gaussian splatting for 360 degree surface reconstruction \
Wenhao Rao, **Yanming Yang**, He Wang*
