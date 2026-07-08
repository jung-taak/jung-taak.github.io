---
title: "Ordinal Neural Collapse as a Representation Prior for Visual Navigation"
collection: publications
category: conferences
permalink: /publication/2026-06-25-ordinal-neural-collapse-visual-navigation
date: 2026-06-25
venue: "European Conference on Computer Vision (ECCV)"
header:
  teaser: "ORION.png"
paperurl: "https://arxiv.org/abs/2606.26839"
citation: 'Son, E.-I.*, Kim, J.-T.*, Seo, S.-W. (2026). &quot;Ordinal Neural Collapse as a Representation Prior for Visual Navigation.&quot; <i>European Conference on Computer Vision (ECCV)</i>. (* Equal contribution)'
---

Learning robust navigation policies directly from visual observations remains a fundamental challenge in vision-based robotic navigation. In end-to-end imitation learning approaches, the visual encoder and action decoder are jointly optimized using a single action loss, which provides only an indirect supervisory signal to the encoder. This indirect supervision frequently results in the encoder learning ambiguous, action-agnostic representations. The problem is further complicated by substantial variations in scene structure and appearance across diverse environments, as well as the prevalence of visual distractors inherent to real-world navigation settings. Such action-agnostic features cause the navigation policy to produce inconsistent actions at ambiguous decision points, leading to navigation failure. To overcome these limitations, we propose ORION (Ordinal Neural Collapse for Visual Navigation), a method that explicitly organizes the encoder's representation space according to the ordinal structure of navigation actions. In the context of goal-directed navigation, ego-centric control categories from Far Left to Far Right exhibit a natural ordinal relationship in which neighboring classes share similar visual contexts, while semantically opposing classes differ substantially in appearance. We encourage class representations to be arranged sequentially along a single discriminative axis, while suppressing off-axis variance within each class. The pretrained encoder is then integrated into a diffusion-based navigation framework, and the full pipeline is fine-tuned end-to-end. Extensive experiments in both simulation and real-world settings show that ORION consistently outperforms end-to-end and neural collapse baselines in navigation success rate and goal progress, with notable gains in visually challenging scenarios such as complex multi-way intersections.
