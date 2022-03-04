---
layout: post
title: DSC180B Section A09: Cross Correlation Experimentation
description: Authors: Harsha Jagarlamudi, Kelly Kong
---

# Cross Correlation

## Background
Climate change is one of the top issues of today. Not only is it a global issue, but it affects all species due to mostly human activity. Tracking the biodiversity of species, specifically birds in this case, can help us gauge how much climate change has damaged these populations and the undergoing changes in their habitats and ecosystem. Our focus is on birds and we’re hoping to use bird audio to measure the biodiversity of birds within our area and potentially identify endangered birds. We want to be able to passively identify and differentiate these birds in a reliable way.

The issue with trying to approach this problem via machine learning models or neural networks is that these models need labeled and identified audio recordings which require manual input and time. Manual audio data labeling, while having the potential to be more accurate than automated methods, is a very time-consuming process and can be prone to inconsistencies due to human input error. These problems can all negatively impact the model and leads us to believe that it is worth looking into an alternative to manual audio labeling in order to generate sufficient audio data for acoustic biodiversity models.

### Data

The datasets that were used have been collected by the San Diego Zoo, which contain .wav files of bird audio from different sources. The primary data we use for this pipeline come from the Scripps Coastal Audio Reserve and Peru and is unlabeled data. The remaining data is sources from the UCSD Engineers for Exploration team and represent labeled bird audio that is titled with the name of the species of interest. 

Each dataset the San Diego Zoo Conservation Technology Lab (CTL) shares with UCSD Engineers for Exploration will remain the property of San Diego Zoo Wildlife Alliance (SDZWA) and cannot be shared or disseminated any further without first following up with the CTL.

## Overview

Our solution is the cross correlation pipeline, which helps to label the data automatically. Cross correlation takes in a template audio clip and runs it across other audio clips to find similarities in peaks; these similarities allow us to identify the same species. 

If we can improve the workflow and speed up the process of gathering training data without sacrificing accuracy, we will be able to gather intel on the biodiversity of species. Monitoring wildlife gives us a better understanding of rare, threatened, or endangered species to help us reallocate funds and provide assistance and protection to those species that need it.

## Methodology / Model

lorem ipsum

### Analysis 

lorem ipsum

## Results / Conclusion

lorem ipsum
