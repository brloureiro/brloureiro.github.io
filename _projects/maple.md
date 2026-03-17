---
layout: page
title: "" 
description: 
permalink: /projects/maple/

pi:
  - name: Bruno Loureiro
    role: Principal Investigator
    image: /assets/img/projects/maple/loureiro.png
    url: /

collaborators:
  - name: Arie Wortsman
    role: PhD student
    image: /assets/img/projects/maple/wortsman.png
    url: https://scholar.google.com/citations?user=O3qupqEAAAAJ&hl=en
  - name: Leonardo Defilippis
    role: PhD student
    image: /assets/img/projects/maple/defilippis.png
    url: https://scholar.google.com/citations?user=-df-QMIAAAAJ&hl=en
  - name: Pierre Mergny
    role: Postdoc
    image: /assets/img/projects/maple/mergny.png
---

![MAPLE logo](/assets/img/projects/maple/maple_logo.png){: style="width: 100%; max-width: 700px; display: block; margin: 0 auto 2rem auto;" }

The [ANR](https://anr.fr/) project *Mathematical Analysis of Pattern Learning and Extraction* (MAPLE) aims to address one of the most pressing questions in modern machine learning: how neural networks learn features from data and how it impacts their generalisation abilities. Despite their widespread success, the mathematical mechanisms that drive feature learning in deep neural networks remain poorly understood. This gap hinders our ability to design more efficient, scalable models, especially in an era where computational resources are becoming increasingly scarce. MAPLE seeks to establish a comprehensive mathematical framework that explains how neural networks adapt to data during training, with a particular focus on representational learning. The project addresses three core questions: 

1. How do neural networks adapt to the structure of data? 
2. How do architectural choices, such as convolutional networks or transformers, influence the representations learned? 
3. How does the emergent capabilities of neural networks arise from feature learning? 

## Principal Investigator

{% include people_grid.liquid people=page.pi %}

## Project members

{% include people_grid.liquid people=page.collaborators %}

<section class="project-section project-publications">
  <h2>Project publications</h2>
  <div class="publications">
    {% bibliography --query @*[maple=true] %}
  </div>
</section>

## Funding

![ANR](/assets/img/projects/maple/anr.jpg){: width="400px" }