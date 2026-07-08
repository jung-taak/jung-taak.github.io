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

### Research Interests
- Learning-based autonomous navigation
- Visual navigation
- Diffusion policy
- Path planning
- Safety of learning-based navigation models

<a id="publications"></a>

Publications
======
{% for post in site.publications reversed %}
  {% include entry-row.html %}
{% endfor %}

<a id="projects"></a>

Projects
======
{% for post in site.projects reversed %}
  {% include entry-row.html %}
{% endfor %}

<a id="awards"></a>

Awards
======
<div style="display: flex; align-items: flex-start; gap: 1.5em; margin-bottom: 2em; flex-wrap: wrap;">
  <div style="flex: 0 0 auto; width: 200px; max-width: 100%; height: 140px; position: relative; overflow: hidden; border-radius: 6px; background-color: var(--global-bg-color);">
    <img src="/images/earth_rover_challenge.jpeg" alt="" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1 1 300px; min-width: 0;">
    <h3 style="margin-top: 0; margin-bottom: 0.25em;">1st Place — Earth Rovers Challenge</h3>
    <p>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Oct 2024</p>
  </div>
</div>
