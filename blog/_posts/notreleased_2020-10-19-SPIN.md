---
layout: post
title: "Towards Safe Policy Improvement for Non-Stationary MDPs"
permalink: /blog/spin
comments: true
tags:
    - timeseries
    - nonstationary
    - reinforcement
    - safety
    - bootstrap
excerpt: "How do we create model-free algorithms that can search for a good policy in a non-stationary MDP?"
---




<div class="message">
 This post is based on a NeurIPS 2020 paper that I worked on with <a href=""> Scott Jordan</a>, <a href="https://research.adobe.com/person/georgios-theocharous/"> Georgios Theocharous</a>, <a href="https://webdocs.cs.ualberta.ca/~whitem/">Martha White</a>, and <a href="https://people.cs.umass.edu/~pthomas/">Philip Thomas</a>. Here are the links for the <a href="https://arxiv.org/abs/2010.12645"> paper</a> and the <a href="https://github.com/ScottJordan/SafePolicyImprovementNonstationary">code</a>.
</div>


## Motivation and probelm

- Example scenarios
- Ask the two main questions

## Forecasting 

- Compare stationary and non-stationary (Two new images)
- Generlizing thes tatioanry setting
- Raise the question that will lead to off-policy

 <p align="center">
 <img src="/images/blog/spin/SafeNSRLidea.png" alt="idea" style="width: 65%; border-radius:0%" />
 </p>


## Overall methodology

something something
 
 
 
 <p align="center">
     <img src="/images/blog/spin/SafeNSRL.png" alt="seldonian" style="vertical-align:middle; width: 65%; margin:0px 10px; border-radius:0%" />
     </p>
 

- Forecasting (add image)
- Gradient computation
- benefits

## Searching for a candidate policy

 <p align="center">
     <img src="/images/blog/spin/diffLB.png" alt="candidate" style="vertical-align:middle; width: 70%; margin:0px 10px; border-radius:0%" />
     </p>
- Discuss


## Empirical performance


 <p align="center">
 <img src="/images/blog/spin/results.png" alt="results" style="vertical-align:middle; width: 60%; margin:0px 10px; border-radius:0%" />
 </p>
 
<br>

- Plots and results


### Open questions
- Discuss variance reduction briefly
- Better off-policy methods OPE
- Better Time-series methods




Cum sociis natoque penatibus et magnis <a href="#">dis parturient montes</a>, nascetur ridiculus mus. *Aenean eu leo quam.* Pellentesque ornare sem lacinia quam venenatis vestibulum. Sed posuere consectetur est at lobortis. Cras mattis consectetur purus sit amet fermentum.

> Curabitur blandit tempus porttitor. Nullam quis risus eget urna mollis ornare vel eu leo. Nullam id dolor id nibh ultricies vehicula ut id elit.

Etiam porta **sem malesuada magna** mollis euismod. Cras mattis consectetur purus sit amet fermentum. Aenean lacinia bibendum nulla sed consectetur.


$$
\begin{align*}
  & \phi(x,y) = \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right)
  = \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j) = \\
  & (x_1, \ldots, x_n) \left( \begin{array}{ccc}
      \phi(e_1, e_1) & \cdots & \phi(e_1, e_n) \\
      \vdots & \ddots & \vdots \\
      \phi(e_n, e_1) & \cdots & \phi(e_n, e_n)
    \end{array} \right)
  \left( \begin{array}{c}
      y_1 \\
      \vdots \\
      y_n
    \end{array} \right)
\end{align*}
$$

