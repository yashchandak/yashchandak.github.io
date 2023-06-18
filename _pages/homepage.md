---
layout: index
title: homepage
excerpt_separator:  <!--more-->
---

<style>

table {
  margin-bottom: 1rem;
  width: 100%;
  font-size: 85%;
  border: 0px solid $border-color;
  border-collapse: collapse;
}

td,
th {
  padding: 1rem .25rem;
  border: 0px solid $border-color;
}

th {
  text-align: left;
}

tbody tr:nth-child(odd) td,
tbody tr:nth-child(odd) th {
  background-color: transparent;
}

paper {
 color: #; 
 font-weight:bold;
}

</style>


<br>

<!--<img align="left" width=150px src="/images/dp.jpg"> -->

I work as a postdoc for [Prof. Emma Brunskill](https://cs.stanford.edu/people/ebrun/) at [Stanford University](https://www.stanford.edu/). My research interests are mostly at the intersection of reinforcement learning and machine learning, specifically on the sub-topics related to continual learning, non-stationarity, safety, off-policy data, and other challenges stemming from real-world applications in education and healthcare.

<br>
I received my PhD at the [University of Massachusetts](https://www.umass.edu/), where I was a member of the [Autonomous Learning Lab (ALL)](http://www-all.cs.umass.edu/) and was fortunate to be advised by [Prof. Philip Thomas](https://people.cs.umass.edu/~pthomas/).


<br>  
My Resume/CV can be found [here](/docs/Resume.pdf)

<br>

## Recent

- Our papers on (a) Representations and Exploration for Deep Reinforcement Learning using Singular Value Decomposition, and (b) Understanding Self-Predictive Learning for Reinforcement Learning , got accepted at ICML'23.
- Our paper on obtaining asymptotically unbiased off-policy policy evaluation when reusing old data in nonstationary environments got accepted at AISTATS'23.
- Our papers on (a) Off-Policy evaluation for action-dependent non-stationary environments, and (b) Factored distributionally robust policies for contextual bandits, got accepted at NeurIPS'22.
- PhD done. Graduated! Thanks to Phil for making my PhD journey amazing!
- RLDM 2022 best paper award for our work on universal off-policy evaluation.
<br><br>

## Selected Publications
Click [here](/publication) for all the publications.

<br>

<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">
     
<tr>
       <td width="14%"  valign="middle">
            <img src="/images/publications/web_activeNSDP.png" alt="activeNSDP" style="vertical-align:middle; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Off-Policy Evaluation for Action-Dependent Non-stationary Environments</paper>
              <br>  
              <b>Yash Chandak</b>,    
              <a href='https://scholar.google.com/citations?user=yK56jugAAAAJ&hl=en'>Shiv Shankar</a>,
              <a href='https://scholar.google.com/citations?user=M2aMMxQAAAAJ&hl=en'>Nathaniel D. Bastian</a>,
              <a href='https://people.cs.umass.edu/~bsilva/'>Bruno Castro da Silva</a>,
              <a href='https://cs.stanford.edu/people/ebrun/'>Emma Brunskill</a>,
              <a href='https://people.cs.umass.edu/~pthomas/'>Philip Thomas</a>
            <br>
       Thirty-sixth Conference on Neural Information Processing Systems (NeurIPS 2022)
              <details>
                <summary>Abstract  |  <a href="https://arxiv.org/abs/2301.10330">Arxiv</a> |  <a href="https://github.com/yashchandak/activeNS">Code</a> | <a href="https://nips.cc/virtual/2022/poster/54093">Video</a>   </summary>            
                  <p class="message">
                  Methods for sequential decision-making are often built upon a foundational assumption that the underlying decision process is stationary. This limits the application of such methods because real-world problems are often subject to changes due to external factors (\textit{passive} non-stationarity), changes induced by interactions with the system itself (\textit{active} non-stationarity), or both (\textit{hybrid} non-stationarity). In this work, we take the first steps towards the fundamental challenge of on-policy and off-policy evaluation amidst structured changes due to active, passive, or hybrid non-stationarity. Towards this goal, we make a \textit{higher-order stationarity} assumption such that non-stationarity results in changes over time, but the way changes happen is fixed. We propose, OPEN, an algorithm that uses a double application of counterfactual reasoning and a novel importance-weighted instrument-variable regression to obtain both a lower bias and a lower variance estimate of the structure in the changes of a policy's past performances. Finally, we show promising results on how OPEN can be used to predict future performances for several domains inspired by real-world applications that exhibit non-stationarity.
                  </p>
              </details>
          </p>  
     </td>
   </tr> 

<tr>
     <td width="14%"  valign="middle">
            <img src="/images/publications/web_UnO.png" alt="UnO" style="vertical-align:middle; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Universal Off-Policy Evaluation</paper>
              <br>
              <b>Yash Chandak</b>,  
              <a href='https://www.cs.utexas.edu/~sniekum/'>Scott Niekum</a>,
              <a href='https://people.cs.umass.edu/~bsilva/'>Bruno Castro da Silva</a>,
              <a href='https://people.cs.umass.edu/~elm/'>Erik Learned-Miller</a>,
              <a href='https://cs.stanford.edu/people/ebrun/'>Emma Brunskill</a>,
              <a href='https://people.cs.umass.edu/~pthomas/'>Philip Thomas</a>
              <br>
             Thirty-fifth Conference on Neural Information Processing Systems (NeurIPS 2021)
            <br>
            5th Multidisciplinary Conference on Reinforcement Learning and Decision Making (RLDM 2022)
            <br>
              <font color='red'>Best Paper Award at RLDM.</font>
              <details>
                <summary>Abstract  | <a href="https://arxiv.org/abs/2104.12820">Arxiv</a> |  <a href="https://github.com/yashchandak/UnO">Code</a>   | <a href="https://slideslive.com/38967385/universal-offpolicy-evaluation?ref=search-presentations-high+confidence">Video</a> | <a href="https://slideslive.com/38972013/advances-in-highconfidence-offpolicy-evaluation?ref=search-presentations-high+confidence">Tutorial</a>  </summary>            
                  <p class="message">
                   When faced with sequential decision-making problems, it is often useful to be able to predict what would happen if decisions were made using a new policy. Those predictions must often be based on data collected under some previously used decision-making rule. Many previous methods enable such off-policy (or counterfactual) estimation of the expected value of a performance measure called the return. In this paper, we take the first steps towards a universal off-policy estimator (UnO) -- one that provides off-policy estimates and high-confidence bounds for any parameter of the return distribution. We use UnO for estimating and simultaneously bounding the mean, variance, quantiles/median, inter-quantile range, CVaR, and the entire cumulative distribution of returns. Finally, we also discuss Uno's applicability in various settings, including fully observable, partially observable (i.e., with unobserved confounders), Markovian, non-Markovian, stationary, smoothly non-stationary, and discrete distribution shifts. 
                  </p>
              </details>
          </p>  
     </td>
   </tr>
 

   <tr>
     <td width="14%"  valign="middle">
            <img src="/images/publications/SPIN.png" alt="SPIN" style="vertical-align:middle; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Towards Safe Policy Improvement for Non-Stationary MDPs</paper>
              <br>
              <b>Yash Chandak</b>,
              <a href='https://people.cs.umass.edu/~sjordan/'>Scott Jordan</a>,
              <a href='https://research.adobe.com/person/georgios-theocharous/'>Georgios Theocharous</a>,   
              <a href='https://webdocs.cs.ualberta.ca/~whitem/'>Martha White</a>,   
              <a href='https://people.cs.umass.edu/~pthomas/'>Philip Thomas</a>
              <br>
              <b>(Spotlight)</b> Thirty-fourth Conference on Neural Information Processing Systems (NeurIPS 2020)
              <details>
                <summary>Abstract | <a href="https://arxiv.org/abs/2010.12645">Arxiv</a> |  <a href="/blog/spin">Blogpost</a> |  <a href="https://github.com/ScottJordan/SafePolicyImprovementNonstationary">Code</a> | <a href="https://nips.cc/virtual/2020/public/poster_680390c55bbd9ce416d1d69a9ab4760d.html">Video</a>  </summary>            
                  <p class="message">
                    Many real-world sequential decision-making problems involve critical systems that present both human-life and financial risks. While several works in the past have proposed methods that are safe for deployment, they assume that the underlying problem is stationary. However, many real-world problems of interest exhibit non-stationarity, and when stakes are high, the cost associated with a false stationarity assumption may be unacceptable. Addressing safety in the presence of non-stationarity remains an open question in the literature. We present a type of Seldonian algorithm (Thomas et al., 2019), taking the first steps towards ensuring safety, with high confidence, for smoothly varying non-stationary decision problems, through a synthesis of model-free reinforcement learning algorithms with methods from time-series analysis.
                  </p>
              </details>
          </p>  
     </td>
   </tr>


   <tr>
     <td width="14%"  valign="middle">
            <img src="/images/publications/prognosticator.png" alt="Future" style="vertical-align:middle; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Optimizing for the Future in Non-Stationary MDPs</paper>
              <br>
              <b>Yash Chandak</b>, 
              <a href='https://research.adobe.com/person/georgios-theocharous/'>Georgios Theocharous</a>,   
              <a href='https://scholar.google.com/citations?user=yK56jugAAAAJ&hl=en'>Shiv Shankar</a>,
              <a href='https://webdocs.cs.ualberta.ca/~whitem/'>Martha White</a>,   
              <a href='https://people.cs.umass.edu/~mahadeva/Site/About_Me.html'>Sridhar Mahadevan</a>,  
              <a href='https://people.cs.umass.edu/~pthomas/'>Philip Thomas</a>
              <br>
              Thirty-seventh International Conference on Machine Learning (ICML 2020)
              <details>
                <summary>Abstract | <a href="https://arxiv.org/abs/2005.08158">Arxiv</a> |  <a href="/blog/prognosticator">Blogpost</a> |  <a href="https://github.com/yashchandak/OptFuture_NSMDP">Code</a> | <a href="https://icml.cc/virtual/2020/poster/6316">Video</a> </summary>            
                  <p class="message">
                    Most reinforcement learning methods are based upon the key assumption that the transition dynamics and reward functions are fixed, that is, the underlying Markov decision process is stationary. However, in many real-world applications, this assumption is violated, and using existing algorithms may result in a performance lag. To proactively search for a good future policy, we present a policy gradient algorithm that maximizes a forecast of future performance. This forecast is obtained by fitting a curve to the counter-factual estimates of policy performance over time, without explicitly modeling the underlying non-stationarity. The resulting algorithm amounts to a non-uniform reweighting of past data, and we observe that minimizing performance over some of the data from past episodes can be beneficial when searching for a policy that maximizes future performance. We show that our algorithm, called Prognosticator, is more robust to non-stationarity than two online adaptation techniques, on three simulated problems motivated by real-world applications. 
                  </p>
              </details>
          </p>  
     </td>
   </tr>


   <tr>
     <td width="14%"  valign="middle">
            <img src="/images/publications/LAICA.png" alt="SAS" style="vertical-align:middle; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Lifelong Learning with a Changing Action Set</paper>
              <br>
              <b>Yash Chandak</b>, 
              <a href='https://research.adobe.com/person/georgios-theocharous/'>Georgios Theocharous</a>,   
              <a href='https://scholar.google.com/citations?user=clEBNJAAAAAJ&hl=en'>Chris Nota</a>, 
              <a href='https://people.cs.umass.edu/~pthomas/'>Philip Thomas</a>
              <br>
              <b>(Oral)</b> Thirty-fourth AAAI Conference on Artificial Intelligence (AAAI 2020)
              <br>
              <font color='red'>Outstanding Student Paper Honorable Mention.</font>
              <details>
                <summary>Abstract | <a href="https://arxiv.org/abs/1906.01770">Arxiv</a> | <a href="https://github.com/yashchandak/lifelong_changing_actions">Code</a> </summary>             
                  <p class="message">
                    In many real-world sequential decision making problems, the number of available actions (decisions) can vary over time. While problems like catastrophic forgetting, changing transition dynamics, changing rewards functions, etc. have been well-studied in the lifelong learning literature, the setting where the action set changes remains unaddressed. In this paper, we present an algorithm that autonomously adapts to an action set whose size changes over time. To tackle this open problem, we break it into two problems that can be solved iteratively: inferring the underlying, unknown, structure in the space of actions and optimizing a policy that leverages this structure. We demonstrate the efficiency of this approach on large-scale real-world lifelong learning problems. 
                  </p>
              </details>
          </p>  
     </td>
   </tr>


   
</table>

<br>



