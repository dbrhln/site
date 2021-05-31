---
layout: page
title: Sequential Effects
description: Do recent experiences influence categorisation?
img: /assets/img/p-cat.jpg
#redirect: https://unsplash.com
importance: 1
category: work
---

The study of categorisation examines what affects how quickly and accurately people are able to classify various stimuli. This has largely focused on long-term knowledge and representations of the stimulus space. For example, when people are classifying a shirt as cheap or expensive, they may draw upon their knowledge of the entire range of shirt prices and be faster and more accurate in classification when the shirts presented lie on either end of the range. However, your perception of the value of a shirt may be influenced by another shirt that you had just seen. A \$100 shirt may seem expensive if presented after a \$20 shirt but may appear cheap if presented after a \$1000 shirt. My work in this area explores the effect of recent experiences on categorisation of stimuli with separable dimensions (or attributes).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/IntegralStim.png' | relative_url }}"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/SeparableStim.png' | relative_url }}"/>
    </div>
</div>
<div class="caption">
    Examples of stimuli with integral dimensions (on the left) and stimuli with separable dimensions (on the right). Integral dimensions, such as hue and saturation, are difficult to attend independently, while separable dimensions, such as size and shape, are easy to selectively attend to without interference from the other dimension.
</div>

This work follows <a href="https://pubmed.ncbi.nlm.nih.gov/27472912/">Little, Wang, and Nosofsky (2016)</a> who established that, when presented with integral-dimension stimuli, categorisation speed and accuracy of stimuli near the category boundary are influenced by the immediately preceding stimulus. They identify 4 main sequential effects:

1. *Repetition effect*: faster and more accurate when preceded by the same stimulus
2. *Push effect*: slower and less accurate when preceded by a highly dissimilar same category stimulus
3. *Pull effect*: slower and less accurate when preceded by a very similar different category stimulus
4. *Changes in the irrelevant dimension* attenuate the first three effects

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/SE_BoxcarStim.png' | relative_url }}"/>
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/GIF_SE_full.gif' | relative_url }}"/>
    </div>
</div>
<div class="caption">
    Stimuli with separable dimensions (saturation and line position) used in Lin & Little (2020) on the left, and an animation of the repetition, push, and pull effects on the right.
</div>

### Selected Work


  <img src="{{ '/assets/img/SE_Results.png' | relative_url }}" align="right" style="width: 12vw; min-width: 330px;"/>

  * Lin, D. J. & Little, D. R. (2020). Further tests of sequence-sensitive models in a modified Garner task using separable dimensions. *PsyArXiv.* <a href="https://psyarxiv.com/4r8tw/" target="_blank">Link</a> and <a href="https://github.com/knowlabUnimelb/MODGARNER/" target="_blank">code</a>.
    - Establishes that the same pattern of sequential effects are found for separable dimension stimuli and demonstrates that a sequence-sensitive feature-based model (with an LBA back end) where only one dimension is attended to best fits the data
  * Lin, D. & Little, D. R. (2017). Sequential Effects in the Garner Task. *Proceedings of the 39th Annual Conference of the Cognitive Science Society*. <a href="https://cogsci.mindmodeling.org/2017/papers/0150/paper0150.pdf" target="_blank">Link</a>
    - Replicates the original Garner speeded classification task with new analysis of sequential effects in a hierarchical Bayesian framework
