---
title: "Parallel Chromatic MCMC with Spatial Partitioning"
collection: publications
permalink: /publications/ChromaticMCMC
venue: "AAAI-17 Distributed Machine Learning Workshop"
date: 2017-2-7
citation: '<b>Jun Song</b>, David A.Moore. <i>AAAI-17 Distributed Machine Learning Workshop</i>. '
---
[[ArXiv]](https://arxiv.org/abs/1612.00595) [[AAAI Version]](https://aaai.org/ocs/index.php/WS/AAAIW17/paper/view/15079) [[Code]](To be updated) [[Slide]](http://kadysongbb.github.io/files/2017-02-07-aaai-chromatic-mcmc.pdf)


## Abstract
We introduce a novel approach for parallelizing MCMC inference in models with spatially determined conditional independence relationships, for which existing techniques exploiting graphical model structure are not applicable. Our approach is motivated by a model of seismic events and signals, where events detected in distant regions are approximately independent given those in intermediate regions. We perform parallel inference by coloring a factor graph defined over regions of latent space, rather than individual model variables. Evaluating on a model of seismic event detection, we achieve significant speedups over serial MCMC with no degradation in inference quality.