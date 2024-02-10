---
layout: home
title: Home
home_title: Concept-based Interpretable Machine Learning
subtitle:
nav_title: Home
permalink: /
description: "Submission for ICML 2024's Call for Tutorials. Please note that this tutorial is <span style='color:red;'><b>under review</b></span> and therefore <span style='color:red;'><b>it may not be included</b></span> as part of the main program."
---


## Introduction

From the moment artificial intelligence (AI) drifted away from symbolic and low-parametric models into the realm of powerful but opaque deep neural networks (DNNs), the AI community has strived to understand how these models learn and reason.
Today, the lack of transparency of such complex models is taking a significant spot in the public discourse as unintended consequences of using "unauditeable" models have become apparent \[[1](https://www.nature.com/articles/s42256-021-00338-7), [2](https://www.nytimes.com/2017/06/13/opinion/how-computers-are-harming-criminal-justice.html), [3](https://www.sacbee.com/news/california/fires/article216227775.html), [4](https://us.macmillan.com/books/9781250074317/automatinginequality), [5](https://www.nature.com/articles/d41586-019-03228-6), [6](https://www.nature.com/articles/s41746-019-0105-1)\].
As we move towards an era in which highly parametric models begin to permeate various facets of our lives, it has become paramount for the AI community to explore practical mechanisms to make these models interpretable.


*Concept representation Learning* (CL) \[[7](https://proceedings.mlr.press/v80/kim18d.html), [8](https://netdissect.csail.mit.edu/), [9](https://proceedings.mlr.press/v119/koh20a.html), [10](https://www.nature.com/articles/s42256-020-00265-z), [11](https://arxiv.org/abs/2209.09056), [12](https://arxiv.org/abs/2304.14068)\], a highly active subfield of Explainable AI (XAI), has recently gained attention as a promising approach for addressing the opacity of modern neural architectures.
Methods within this family circumvent the complexity in a DNN's reasoning process by forcing such reasoning to depend on intermediate high-level units of information called *concepts*.
Under this paradigm, a model can construct an explanation for its predictions using representations that are aligned with a "vocabulary" similar to that used by an expert on the same task (e.g., predicting a knee has grade-4 osteoarthritis because it has "decreased synovial fluid" and "reduced joint space").


Concept-based reasoning encourages a model to learn to explain its outputs using higher-level representations than its possibly individually uninformative input features (e.g., pixels). As representations for these concepts can be learnt or discovered by differentiable DNNs in an end-to-end fashion, CL provides a promising framework for constructing interpretable architectures and concept representations without losing the expressivity that lies behind the success of current DNNs; all while aligning a model's reasoning to concept-based reasoning common amongst humans. Such flexibility has enabled CL to quickly evolve into a highly inter-disciplinary field with strong connections to other active research areas within representation learning.


This tutorial seeks to equip machine learning researchers and engineers with the necessary background to understand how to use and expand some of the tools proposed within CL in their respective areas of interest. We achieve this by appealing to newcomers to the field through discussions of foundational works within CL and appealing to experienced CL researchers through discussions of very recent directions. With these goals in mind, this tutorial will begin by motivating the need and importance of CL in the modern AI ecosystem and then proceed by expanding on the state of the field through three technical sections. We will then conclude our tutorial by focusing on open questions within CL and establishing a list of challenges which we believe could be solved in the next few years, hopefully encouraging a fruitful discussion on how to best tackle these challenges. We hope that by the end of this tutorial, the audience will be able to comfortably identify the areas of CL that may be useful for their work and will leave with a deeper understanding of some of the crucial open research questions within CL.

## Important Details

[This is a proposal for a tutorial which is <span style='color:red;'><b>still under review</b></span>. When a decision is made, we will update this website accordingly.]

- **Date**: If accepted, this tutorial will be on Monday July 22nd, 2024 (tutorial will last two hours, time TBD)
- **Conference**: The Forty-first [International Conference on Machine Learning (ICML)](https://icml.cc/)
- **Location**: [Messe Wien Exhibition Congress Center, Vienna, Austria](https://www.messecongress.at/)
- **Modality**: In-person event (livestreamed option will be available for online attendants)

Our tutorial's material will assume a basic knowledge of ML (e.g., foundations of supervised learning, experimental design, basic probabilistic modelling, etc.), with particular emphasis on a solid Deep Learning foundation (e.g., tensor calculus, neural networks, backpropagation, etc.). Concepts that may require mathematical tools/expertise beyond those one would expect to be shared among the ICML community will be introduced in the tutorial as a refresher.

All relevant material used and discussed during the tutorial will be made available through [here](/tutorial) immediatedly after the tutorial is over.



## Presenters
  <div class="row projects pt-1 pb-1">
      <div class="col-sm-4">
          {% include people.html name="Mateo Espinosa Zarlenga" affiliation="University of Cambridge" url="https://mateoespinosa.github.io/" img="/assets/img/people/mateo_2.jpg" %}
      </div>
      <div class="col-sm-4">
        {% include people.html name="Pietro Barbiero" affiliation="Università della Svizzera Italiana" url="https://www.pietrobarbiero.eu/" img="/assets/img/people/pietro.jpeg" %}
      </div>
  </div>


For any questions, please do not hesitate to contact Mateo at
[me466@cam.ac.uk](mailto:me466@cam.ac.uk).
