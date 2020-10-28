---
layout: post
title: "Optimizing for the Future in Non-Stationary MDPs"
permalink: /blog/optimizing_future_NSMDP
comments: true
tags:
    - timeseries
    - nonstationary
    - reinforcement
excerpt: "How do we create model-free algorithms that can search for a good policy in a non-stationary MDP?"
---




<div class="message">
  This post is based on an ICML 2020 paper that I worked on with <a href="https://research.adobe.com/person/georgios-theocharous/"> Georgios Theocharous </a>, <a href="https://scholar.google.com/citations?user=yK56jugAAAAJ&hl=en">Shiv Shankar</a>, <a href="https://webdocs.cs.ualberta.ca/~whitem/">Martha White</a>, <a href="https://people.cs.umass.edu/~mahadeva/Site/About_Me.html">Sridhar Mahadevan</a>, and <a href="https://people.cs.umass.edu/~pthomas/">Philip Thomas</a>. Here are the links for the <a href="https://arxiv.org/abs/2005.08158"> paper </a>  and the <a href="https://github.com/yashchandak/OptFuture_NSMDP"> code</a>.
</div>


How do we create model-free algorithms that can search for a good policy in a non-stationary MDP?


- Example scenarios
- Ask the two main questions

## A time-series perspective    

- Compare stationary and non-stationary (Two new images)
- Generlizing thes tatioanry setting
- Raise the question that will lead to off-policy


 <p align="center">
 <img src="/images/blog/optfuture/Eval.png" alt="eval" style="width: 30%; border-radius:0%" />
 </p>
 
 

## Optimizing the future performance

something something
 
 <p align="center">
     <img src="/images/blog/optfuture/idea.png" alt="idea" style="vertical-align:middle; width: 30%; margin:0px 10px; border-radius:0%" />
     </p>
 

- Forecasting (add image)
- Least-squares regression as a differntiable operation
- Generalizes stationary setting
- Gradient computation
- benefits


## An intriguing behavior 

 <p align="center">
     <img src="/images/blog/optfuture/weights.png" alt="idea" style="vertical-align:middle; width: 30%; margin:0px 10px; border-radius:0%" />
     </p>
- Discuss
- How do we mitigate variance?



## Empirical performance

   <img align="left" src="/images/blog/optfuture/NS_Reco_speed.png" alt="reacher" style="width: 30%; margin:0px 10px; border-radius:0%" />
 <img align="left" src="/images/blog/optfuture/NS_Reacher_speed.png" alt="reacher" style="width: 30%; margin:0px 10px; border-radius:0%" />      <img src="/images/blog/optfuture/NS_SimGlucose-v0_speed.png" alt="reacher" style="width: 30%; margin:0px 10px; border-radius:0%" />
 
 <p align="center">
  <img src="/images/blog/optfuture/legend.png" alt="reacher" style="width: 30%; margin:0px 10px; border-radius:0%" />
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

