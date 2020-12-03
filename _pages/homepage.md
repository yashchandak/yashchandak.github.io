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
  padding: .25rem .5rem;
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

a[href='red'] {
    color: red;
    pointer-events: none;
    cursor: default;
    text-decoration: none;
}

</style>


<br>

I'm a PhD candidate at the [University of Massachusetts](https://www.umass.edu/). I am also a member of the [Autonomous Learning Lab (ALL)](http://www-all.cs.umass.edu/) and am fortunate to be advised by [Prof. Philip Thomas](https://people.cs.umass.edu/~pthomas/).
My primary interest is in **continual learning**, a branch of Artificial Intelligence, which aims at teaching machines
new concepts over time. My research is mostly at the intersection of reinforcement learning and machine learning, with a focus on challenges of real-world applications. I enjoy reading and looking out for inspirations from neuroscience as well.
<br><br>


## Recent
- Our paper on providing high-confidence off-policy variance estimates got accepted at AAAI'21!
- Our paper on ensuring safe policy improvement for non-stationary MDPs got accepted at NeurIPS'20!
- Our papers on (a) Optmizing for the future in non-stationary MDPs, and (b) Evaluating the performance of RL algorithms, got accepted at ICML'20!
- Received Outstanding Student Paper Honorable Mention by AAAI'20 for our paper on Lifelong Learning with a Changing Action Set.
- Our papers on (a) lifelong learning with a changing action set, and (b) RL when all actions are not always available, got accepted at AAAI'20!  
- I will be interning at Adobe Research under [Sridhar Mahadevan](https://people.cs.umass.edu/~mahadeva/Site/About_Me.html) and [Georgios Theocharous](https://research.adobe.com/person/georgios-theocharous/) during Summer 2019.  

<br>

## Selected Publications
Click [here](/publication) for all the publications.

<br>

<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">

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
                <summary>Abstract | <a href="https://arxiv.org/abs/2010.12645">Arxiv</a> | <a href="/blog/spin">Blogpost</a> | <a href="https://github.com/ScottJordan/SafePolicyImprovementNonstationary">Code</a> | <a href="https://nips.cc/virtual/2020/public/poster_680390c55bbd9ce416d1d69a9ab4760d.html">Video</a>  </summary>            
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
                <summary>Abstract | <a href="https://arxiv.org/abs/2005.08158">Arxiv</a> | <a href="/blog/prognosticator">Blogpost</a> | <a href="https://github.com/yashchandak/OptFuture_NSMDP">Code</a> | <a href="https://icml.cc/virtual/2020/poster/6316">Video</a> </summary>            
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
              <a href="red">Outstanding Student Paper Honorable Mention.</a>
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



