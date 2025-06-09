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

(* denotes corresponding author)

FlowDirector: Training-Free Flow Steering for Precise Text-to-Video Editing \
Guangzhao Li, **Yanming Yang**, Chenxi Song, Chi Zhang*

L3D: Enhancing 2D Talking Portraits Synthesis Learning with Pitch information using 3D Blendshapes Priors \
**Yanming Yang**, Wenhao Rao, Ifat Yasin*

Deformable gaussian splatting for 360 degree surface reconstruction \
Wenhao Rao, **Yanming Yang**, He Wang* 
