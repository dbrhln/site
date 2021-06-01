---
layout: page
title: Decision Making
description:  How do people navigate the exploration-exploitation trade-off?
img: /assets/img/p-dm.jpg
importance: 2
category: work
---
### Ongoing Work
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

### Past Work
A previous research project investigated how people estimate outcome probabilities in decision-making from both description (when outcome probabilities are stated) and experience. In the field, one robust finding is that people tend to underweight rare events in decisions from experience but overweight them in decisions from description (the 'Description-Experience gap'). For example, if people have had a cold for a total of two weeks in the past year (~4% of the time), they behave as though they have less than a ~4% probability of coming down with a cold. However, if they are explicitly told that they have a 4% chance of catching a cold, they behave as though it occurs more often.

We propose that a cognitive model based on exemplar theory, where a memory trace containing information such as value is stored every time a stimulus is encountered, is able to provide a unified account of decisions from description and experience. My work, in particular, focuses on extending an exemplar-based model of decisions from experience developed by Hawkins et al. (2014) to decisions from description. Hawkins et al. (2014) posited that people store each encountered outcome as exemplars of an option with some probability of error and based their estimation of outcome probabilities on the stored exemplars. This was dubbed the *Exemplar-Confusion model* ('ExCon model').

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/Excon-Fig.png' | relative_url }}"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/Excon-BF.png' | relative_url }}"/>
    </div>
</div>
<div class="caption">
    The ExCon model process for decisions from description on the left. Log Bayes Factor comparing the ExCon model with Cumulative Prospect Theory for the 30 participants from Rieskamp (2008) on the right.
</div>

In our model for decisions from description, where outcomes probabilities are known from the outset, we propose that people mentally simulate a set of outcomes which serve as exemplars. We demonstrate that this model performs at least as well as Cumulative Prospect Theory, a benchmark model of decisions from description, while providing a psychological account of the decision making process. Together with the ExCon model for decisions from experience, we show that these two exemplar-based models are able to account for the DE gap.

### Relevant Material
* The online version of my experiment. <a href="https://exp-exp-289600.ts.r.appspot.com/">Link</a> and <a href="https://github.com/dbrhln/EXP-EXP-ONLINE-2020" target="_blank">code</a>
* A visualisation and more information about diffusion models of response times and choice made in R Shiny. <a href="https://dbrhln.shinyapps.io/simulate-DDM/" target="_blank">Link</a>
* Lin, D., Donkin, C., & Newell, B. (2015) The exemplar confusion model: An account of biased probability estimates in decisions from description. *Proceedings of the 37th Annual Conference of the Cognitive Science Society* <a href="http://www2.psy.unsw.edu.au/users/cdonkin/publications/cogsci15a.pdf" target="_blank">Link</a>
