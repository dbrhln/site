---
layout: page
title: Decision Making
description:  How do people navigate the exploration-exploitation trade-off?
img: /assets/img/p-dm.jpg
importance: 2
category: work
---

The field of decision making examines the choices people make when presented with a set of options with uncertain outcomes. Often, these decisions do not entail explicitly stated rewards and outcomes for each option and require learning about the decision environment from experience. For example, when deciding which cafe to get your morning coffee from, you have to rely on your past experience of the cafes nearby and consolidate information, such as the quality of the coffee and the length of the queue, to form an expectation of how rewarding going to each cafe will be. Each morning, based on your experience, you can decide whether to go to your regular cafe that you can rely on for a good cup of coffee even if there is a long queue, or try another cafe that you are less familiar with but might provide you with a comparable quality of coffee and have a shorter queue. Additionally, you may anticipate that your regular cafe will be more crowded for the next few days as it was recently featured in the news.

These repeated decisions between a set of two or more options that you have to learn about over time can be formally characterised as a multi-armed bandit problem. In these problems, people have to navigate a trade-off between exploration (i.e., trying out different options) and exploitation (i.e., sticking with a familiar option) while continually tracking the environment in order to maximise reward over the entire period.

My research examines how people navigate this trade-off in problems where people have to choose between completing tasks of varying difficulty and reward. In particular, my research aims to gain insight into in how difficulty and reward interact to drive exploration and exploitation behaviour, to what extent people rely on past experiences (e.g., whether entire outcome history is considered, and if more recent outcomes carry more weight), how changes in the environment affect behaviour, and ultimately, focuses on developing a parsimonious and psychologically tractable model of the decision making that can account for both choices and response times for decisions from experience.

The model that I propose combines reinforcement learning and diffusion modelling of response times to jointly predict performance in both the tasks that have to be completed to obtain a reward and the decision to switch to a different task (explore) or complete the same task again (exploit).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/Exp-Exp-Rec.gif' | relative_url }}"/>
    </div>
</div>
<div class="caption">
    In the experiment, the participant repeatedly chooses between two motion direction judgment tasks ("Patch A" and "Patch B") of different difficulty levels and reward. The goal is to maximise their total reward over the course of the experiment as they are paid a monetary bonus based on their points accumulated.
</div>

### Relevant Material
* The online version of my experiment. <a href="https://exp-exp-289600.ts.r.appspot.com/">Link</a> and <a href="https://github.com/dbrhln/EXP-EXP-ONLINE-2020">code</a>
* A visualisation and more information about diffusion models of response times and choice made in R Shiny. <a href="https://dbrhln.shinyapps.io/simulate-DDM/">Link</a>
