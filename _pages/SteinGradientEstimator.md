---
permalink: /steingradientestimator/
author_profile: true
layout: archive
---

# Readings: Gradient Estimators for Implicit Models
[Gradient Estimators for Implicit Models](https://arxiv.org/abs/1705.07107), Yingzhen Li and Richard E. Turner, proposed a new gradient estimator, called the Stein Gradient Estimator, for implicit models. This page collects the slide and the Python notebook in my course representation of this paper. The course is [Research Topics in Statistical Machine Learning: Minimization Expectation](https://www.cs.toronto.edu/~cmaddis/courses/sta4273_w21/). 

## Introduction
[Implicit models](https://www.jstor.org/stable/pdf/2345504.pdf), defined as any generation process, are flexible in modeling the samples at the expense of the tractability of the distribution density. Examples include data simulators that are widely used in engineering and scientific research, [generative adversarial networks (GANs)](https://papers.nips.cc/paper/5423-generative-adversarial-nets.pdf) for image sythesis, and the [approximate inference](http://www.cs.columbia.edu/~blei/fogm/2018F/materials/BleiKucukelbirMcAuliffe2017.pdf) techniques relying on implicit distributions. The common methods rely on approximations to the intractable density function or the optimization objective, which may lead to unstable training and poor results. The alternative way is to approximate the gradient well and then apply gradient-based optimizations. Along this line of research, the author proposed Stein Gradient Estimator for implicit models in this paper. 

## Presentation Materials
- [the slide & the Python notebook](https://github.com/HengchaoChen/HengchaoChen.github.io/raw/master/files/STA4273_Presentation.zip)
