---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. student at the Vehicle Intelligence Lab at Seoul National University. My research focuses on learning-based autonomous navigation, with particular emphasis on visual navigation, diffusion policy, and path planning.

Our lab develops and deploys field robots that perform autonomous driving in outdoor and off-road environments. Recently, my work has centered on improving the safety of learning-based navigation models.

Research Interests
======
- Learning-based autonomous navigation
- Visual navigation
- Diffusion policy
- Path planning
- Safety of learning-based navigation models

[Publications](#publications) &middot; [Awards](#awards) &middot; [Projects](#projects)

<a id="publications"></a>

Publications
======
{% include base_path %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<a id="awards"></a>

Awards
======
- **1st Place — Earth Rovers Challenge** at IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Oct 2024

<a id="projects"></a>

Projects
======
{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
