---
layout: page
title: Prisoner's Dilemma in Social Network
description: Cognitive modeling of "irrational" behavior in a rational way.
img: assets/img/pd.png
importance: 1
category: academic
related_publications: 
---

To depict the effect that people believe their actions have on the future behavior of others,
we build a bonded rational model of the prisoner's dilemma game in a social network.

In this model, each agent starts reinforcement learning from scratch, gradually realizing that friendly cooperation leads to cooperation from others.

The cooperation is stable in fixed networks, but not in random networks or litte profits games, which is consistent with the empirical observation.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/pd_1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Simulation with different profits (b) and number of neighbors (k).
</div>
The assortment (cooperators’ average number of cooperative neighbors minus defectors’ average number of cooperative neighbors) also give us a surprising similarity with behavioral experiments.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/assortment.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The assortments in different simulation conditions. Green lind for fixed group with punishment, blue line for fixed group without punishment, red line for random group without punishment.
</div>

