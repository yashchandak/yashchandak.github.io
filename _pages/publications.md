---
permalink: "/publication/"
layout: page
title: Publications
sidebar_link: true
order: 2
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


</style>

#### 2021

<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">
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
              <details>
                <summary>Abstract  | <a href="https://arxiv.org/abs/2104.12820">Arxiv</a> </summary>            
                  <p class="message">
                   When faced with sequential decision-making problems, it is often useful to be able to predict what would happen if decisions were made using a new policy. Those predictions must often be based on data collected under some previously used decision-making rule. Many previous methods enable such off-policy (or counterfactual) estimation of the expected value of a performance measure called the return. In this paper, we take the first steps towards a universal off-policy estimator (UnO) -- one that provides off-policy estimates and high-confidence bounds for any parameter of the return distribution. We use UnO for estimating and simultaneously bounding the mean, variance, quantiles/median, inter-quantile range, CVaR, and the entire cumulative distribution of returns. Finally, we also discuss Uno's applicability in various settings, including fully observable, partially observable (i.e., with unobserved confounders), Markovian, non-Markovian, stationary, smoothly non-stationary, and discrete distribution shifts. 
                  </p>
              </details>
          </p>  
     </td>
   </tr>
  
  
<tr>
       <td width="14%"  valign="middle">
            <img src="/images/publications/web_HCGA.png" alt="HCGA" style="vertical-align:middle; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>High Confidence Generalization for Reinforcement Learning</paper>
              <br> 
              <a href='https://people.cs.umass.edu/~jekostas/jekostas.html'>James Kostas</a>, 
              <b>Yash Chandak</b>,  
              <a href='https://people.cs.umass.edu/~sjordan/'>Scott Jordan</a>,
              <a href='https://research.adobe.com/person/georgios-theocharous/'>Georgios Theocharous</a>, 
              <a href='https://people.cs.umass.edu/~pthomas/'>Philip Thomas</a>
              <br>
              Thirty-eighth International Conference on Machine Learning (ICML 2021)
              <details>
                <summary>Abstract  </summary>            
                  <p class="message">
                   We present several classes of reinforcement learn-ing algorithms that safely generalize toMarkovdecision processes(MDPs) not seen during train-ing.  Specifically, we study the setting in whichsome set of MDPs is accessible for training. Forvarious definitions of safety, our algorithms giveprobabilistic guarantees that agents can safely gen-eralize to MDPs that are sampled from the samedistribution but are not necessarily in the train-ing set.   These algorithms are a type ofSeldo-nianalgorithm (Thomas et al., 2019), which is aclass of machine learning algorithms that returnmodels with probabilistic safety guarantees foruser-specified definitions of safety. 
                  </p>
              </details>
          </p>  
     </td>
   </tr>
  
<tr>
       <td width="14%"  valign="middle">
            <img src="/images/publications/web_SharedAutonomy.png" alt="HumanAI" style="vertical-align:middle; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Intervention Aware Shared Autonomy</paper>
              <br> 
              <a href='https://scholar.google.com/citations?user=-ccuMB4AAAAJ&hl=zh-CN'>Weihao Tan</a>*, 
              <a href='http://davidkoleczek.me/'>David Koleczek</a>*, 
              <a href='https://scholar.google.com/citations?user=FzRyPc0AAAAJ&hl=en'>Siddhant Pradhan</a>*, 
              <a href='http://ds.cs.umass.edu/nicholas-perello'>Nicholas Perello</a>, 
              <a href='https://www.linkedin.com/in/vivekchettiar/'>Vivek Chettiar</a>, 
              <a href='https://yashchandak.github.io/publication/'>Nan Ma</a>, 
              <a href='https://www.linkedin.com/in/aaslesha-rajaram/'>Aaslesha Rajaram</a>, 
              <a href='https://www.linkedin.com/in/vishalrohra1/'>Vishal Rohra</a>, 
              <a href='https://www.linkedin.com/in/soundararajansrinivasan/'>Soundar Srinivasan</a>, 
              <a href='https://sites.google.com/view/sajjadriaj/'>H M Sajjad Hossain</a>^, 
              <b>Yash Chandak</b>^.
            *Equal contribution, ^Equal advising
            <br>
              HumanAI workshop @ Thirty-eighth International Conference on Machine Learning (ICML 2021)
              <details>
                <summary>Abstract </summary>            
                  <p class="message">
                  Shared  autonomy  refers  to  approaches  for  en-abling an autonomous agent to collaborate witha human with the aim of improving human per-formance.  However, besides improving perfor-mance, it may often be beneficial that the agentconcurrently accounts for preserving the user’sexperience or satisfaction of collaboration. In or-der to address this additional goal, we examineapproaches for improving the user experience byconstraining the number of interventions by theautonomous agent. We propose two model-freereinforcement learning methods that can accountfor both hard and soft constraints on the numberof interventions. We show that not only does ourmethod outperform the existing baseline, but alsoeliminates the need to manually tune an arbitraryhyperparameter for controlling the level of assis-tance.  We also provide an in-depth analysis ofintervention scenarios in order to further illumi-nate system understanding.
                  </p>
              </details>
          </p>  
     </td>
   </tr>
  
  
<tr>
  <td width="14%"  valign="middle">
            <img src="/images/publications/HCOVE.png" alt="SPIN" style="vertical-align:middle; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>High Confidence Off-Policy (or Counterfactual) Variance Estimation</paper>
              <br>
              <b>Yash Chandak</b>,  
              <a href='https://scholar.google.com/citations?user=yK56jugAAAAJ&hl=en'>Shiv Shankar</a>,
              <a href='https://people.cs.umass.edu/~pthomas/'>Philip Thomas</a>
              <br>
              Thirty-fifth AAAI Conference on Artificial Intelligence (AAAI 2021)
              <details>
                <summary>Abstract  | <a href="https://arxiv.org/abs/2101.09847">Arxiv</a> </summary>            
                  <p class="message">
                   Many sequential decision-making systems leverage data collected using prior policies to propose a new policy. In critical applications, it is important that high-confidence guarantees on the new policy's behavior are provided before deployment, to ensure that the policy will behave as desired. Prior works have studied high-confidence off-policy estimation of the \emph{expected} return, however, high-confidence off-policy estimation of the \emph{variance} of returns can be equally critical for high-risk applications. In this paper, we tackle the previously open problem of estimating and bounding, with high confidence, the variance of returns from off-policy data.
                  </p>
              </details>
          </p>  
     </td>
   </tr>

  
  
  
</table>

<br>

#### 2020

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
                <summary>Abstract | <a href="https://arxiv.org/abs/2005.08158">Arxiv</a> |  <a href="/blog/prognosticator">Blogpost</a> |  <a href="https://github.com/yashchandak/OptFuture_NSMDP">Code</a> | <a href="https://icml.cc/virtual/2020/poster/6316">Video</a>  </summary>            
                  <p class="message">
                    Most reinforcement learning methods are based upon the key assumption that the transition dynamics and reward functions are fixed, that is, the underlying Markov decision process is stationary. However, in many real-world applications, this assumption is violated, and using existing algorithms may result in a performance lag. To proactively search for a good future policy, we present a policy gradient algorithm that maximizes a forecast of future performance. This forecast is obtained by fitting a curve to the counter-factual estimates of policy performance over time, without explicitly modeling the underlying non-stationarity. The resulting algorithm amounts to a non-uniform reweighting of past data, and we observe that minimizing performance over some of the data from past episodes can be beneficial when searching for a policy that maximizes future performance. We show that our algorithm, called Prognosticator, is more robust to non-stationarity than two online adaptation techniques, on three simulated problems motivated by real-world applications. 
                  </p>
              </details>
          </p>  
     </td>
   </tr>

   <tr>
     <td width="14%"  valign="middle">
            <img src="/images/publications/evalrldm.png" alt="eval" style="vertical-align:middle; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Evaluating the Performance of Reinforcement Learning Algorithms</paper>
              <br>
              <a href='https://people.cs.umass.edu/~sjordan/'>Scott Jordan</a>,
              <b>Yash Chandak</b>,    
              <a href='https://people.cs.umass.edu/~dcohen/'>Daniel Cohen</a>,  
              <a href='https://people.cs.umass.edu/~mengxuezhang/'>Mengxue Zhang</a>,  
              <a href='https://people.cs.umass.edu/~pthomas/'>Philip Thomas</a>
              <br>
              Thirty-seventh International Conference on Machine Learning (ICML 2020)
              <details>
                <summary>Abstract  | <a href="https://arxiv.org/abs/2006.16958">Arxiv</a> | <a href="https://github.com/ScottJordan/EvaluationOfRLAlgs">Code</a> | <a href="https://icml.cc/virtual/2020/poster/6301">Video</a>   </summary>            
                  <p class="message">
                    Performance evaluations are critical for quantifying algorithmic advances in reinforcement learning. Recent reproducibility analyses have shown that reported performance results are often inconsistent and difficult to replicate. In this work, we argue that the inconsistency of performance stems from the use of flawed evaluation metrics. Taking a step towards ensuring that reported results are consistent, we propose a new comprehensive evaluation methodology for reinforcement learning algorithms that produces reliable measurements of performance both on a single environment and when aggregated across environments. We demonstrate this method by evaluating a broad class of reinforcement learning algorithms on standard benchmark tasks. 
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

  <tr>
     <td width="14%"  valign="middle">
            <img src="/images/publications/SAS.jpg" alt="SAS" style="vertical-align:middle; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Reinforcement Learning When All Actions are Not Always Available</paper>
              <br>
              <b>Yash Chandak</b>, 
              <a href='https://research.adobe.com/person/georgios-theocharous/'>Georgios Theocharous</a>,   
              <a href='https://bmetevier.github.io/'>Blossom Metevier</a>, 
              <a href='https://people.cs.umass.edu/~pthomas/'>Philip Thomas</a>
              <br>
              Thirty-fourth AAAI Conference on Artificial Intelligence (AAAI 2020)
              <details>
                <summary>Abstract | <a href="https://arxiv.org/abs/1906.01772">Arxiv</a> | <a href="https://github.com/yashchandak/SAS_RL">Code</a> </summary>            
                  <p class="message">
                   The Markov decision process (MDP) formulation used to model many real-world sequential decision making problems does not capture the setting where the set of available decisions (actions) at each time step is stochastic. Recently, the stochastic action set Markov decision process (SAS-MDP) formulation has been proposed, which captures the concept of a stochastic action set. In this paper we argue that existing RL algorithms for SAS-MDPs suffer from divergence issues, and present new algorithms for SAS-MDPs that incorporate variance reduction techniques unique to this setting, and provide conditions for their convergence. We conclude with experiments that demonstrate the practicality of our approaches using several tasks inspired by real-life use cases wherein the action set is stochastic. 
                  </p>
              </details>
          </p>  
     </td>
   </tr>


  <tr>
     <td width="14%"  valign="middle">
            <img src="/images/publications/cogbias.png" alt="cogbias" style="vertical-align:middle; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Reinforcement Learning for Strategic Recommendations</paper>
              <br>
              <a href='https://research.adobe.com/person/georgios-theocharous/'>Georgios Theocharous</a>, 
              <b>Yash Chandak</b>,   
              <a href='https://people.cs.umass.edu/~pthomas/'>Philip Thomas</a>,
              <a href='https://research.monash.edu/en/persons/frits-de-nijs'>Frits de Nijs</a>
              <br>
              Technical Report
              <details>
                <summary>Abstract | <a href="https://arxiv.org/abs/2009.07346">Arxiv</a> </summary>            
                  <p class="message">
                   Strategic recommendations (SR) refer to the problem where an intelligent agent observes the sequential behaviors and activities of users and decides when and how to interact with them to optimize some long-term objectives, both for the user and the business. These systems are in their infancy in the industry and in need of practical solutions to some fundamental research challenges. At Adobe research, we have been implementing such systems for various use-cases, including points of interest recommendations, tutorial recommendations, next step guidance in multi-media editing software, and ad recommendation for optimizing lifetime value. There are many research challenges when building these systems, such as modeling the sequential behavior of users, deciding when to intervene and offer recommendations without annoying the user, evaluating policies offline with high confidence, safe deployment, non-stationarity, building systems from passive data that do not contain past recommendations, resource constraint optimization in multi-user systems, scaling to large and dynamic actions spaces, and handling and incorporating human cognitive biases. In this paper we cover various use-cases and research challenges we solved to make these systems practical. 
                  </p>
              </details>
          </p>  
     </td>
   </tr>


</table>   




<br>
  

#### 2019

<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">
  
   <tr>
     <td width="14%"  valign="middle">
            <img src="/images/publications/action_rep.png" alt="action_representations" align="middle" style="width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Learning Action Representations for Reinforcement Learning</paper>
              <br>
              <b>Yash Chandak</b>, 
              <a href='https://research.adobe.com/person/georgios-theocharous/'>Georgios Theocharous</a>,   
              <a href='https://people.cs.umass.edu/~jekostas/jekostas.html'>James Kostas</a>, 
              <a href='https://people.cs.umass.edu/~sjordan/'>Scott Jordan</a>,              
              <a href='https://people.cs.umass.edu/~pthomas/'>Philip Thomas</a>
              <br>
              Thirty-sixth International Conference on Machine Learning (ICML 2019)
              <details>
                <summary>Abstract | <a href="https://arxiv.org/abs/1902.00183">Arxiv</a>  | <a href="https://slideslive.com/38917406/reinforcement-learning-theory?ref=speaker-18061-latest">Video</a> </summary>            
                  <p class="message">
                    Most model-free reinforcement learning methods leverage state representations (embeddings) for generalization, but either ignore structure in the space of actions or assume the structure is provided a priori. We show how a policy can be decomposed into a component that acts in a low-dimensional space of action representations and a component that transforms these representations into actual actions. These representations improve generalization over large, finite action sets by allowing the agent to infer the outcomes of actions similar to actions already taken. We provide an algorithm to both learn and use action representations and provide conditions for its convergence. The efficacy of the proposed method is demonstrated on large-scale real-world problems. 
                  </p>
              </details>
          </p>  
     </td>
   </tr>
   
   <tr>
     <td width="14%"  valign="middle">
            <img src="/images/publications/action_rep_2.png" alt="action_generalization" align="middle" style="width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Improving Generalization over Large Action Sets</paper>
              <br>
              <b>Yash Chandak</b>, 
              <a href='https://research.adobe.com/person/georgios-theocharous/'>Georgios Theocharous</a>,   
              <a href='https://people.cs.umass.edu/~jekostas/jekostas.html'>James Kostas</a>, 
              <a href='https://people.cs.umass.edu/~sjordan/'>Scott Jordan</a>,              
              <a href='https://people.cs.umass.edu/~pthomas/'>Philip Thomas</a>
              <br>
              <b>(Oral)</b> 4th Multidisciplinary Conference on Reinforcement Learning and Decision Making (RLDM 2019)
          </p>  
     </td>
   </tr>  
   
   <tr>
     <td width="14%"  valign="middle">
            <img src="/images/publications/eval.png" alt="eval" style="vertical-align:middle; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Evaluating Reinforcement learning Algorithms Using Cumulative Distributions of Performance</paper>
              <br>
              <a href='https://people.cs.umass.edu/~sjordan/'>Scott Jordan</a>,
              <b>Yash Chandak</b>,    
              <a href='https://people.cs.umass.edu/~mengxuezhang/'>Mengxue Zhang</a>,  
              <a href='https://people.cs.umass.edu/~dcohen/'>Daniel Cohen</a>,  
              <a href='https://people.cs.umass.edu/~pthomas/'>Philip Thomas</a>
              <br>
              4th Multidisciplinary Conference on Reinforcement Learning and Decision Making (RLDM 2019)
          </p>  
     </td>
   </tr>
   
  <tr>
     <td width="14%"  valign="middle">
            <img src="/images/publications/bellman_optimal.png" alt="Bellman" align="middle" style="width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Classical Policy Gradient: Preserving Bellman’s Principle of Optimality</paper>
              <br>
              <a href='https://people.cs.umass.edu/~pthomas/'>Philip Thomas</a>,
              <a href='https://people.cs.umass.edu/~sjordan/'>Scott Jordan</a>,                
              <b>Yash Chandak</b>,    
              <a href='https://scholar.google.com/citations?user=clEBNJAAAAAJ&hl=en'>Chris Nota</a>, 
              <a href='https://people.cs.umass.edu/~jekostas/jekostas.html'>James Kostas</a>, 
              <br>
             Technical Report.
              <details>
                <summary>Abstract | <a href="https://arxiv.org/abs/1906.03063">Arxiv</a> </summary>            
                  <p class="message">
                    We propose a new objective function for finite-horizon episodic Markov decision processes that better captures Bellman's principle of optimality, and provide an expression for the gradient of the objective.  
                  </p>
              </details>
          </p>  
     </td>
   </tr>


</table>

<br>
#### 2018

<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">
   <tr>
     <td width="14%"  valign="middle">
            <img src="/images/publications/dynamic_action.png" alt="dynamic_actions" align="middle" style="width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Reinforcement Learning with a Dynamic Action Set</paper>
              <br>
              <b>Yash Chandak</b>, 
              <a href='https://research.adobe.com/person/georgios-theocharous/'>Georgios Theocharous</a>,   
              <a href='https://people.cs.umass.edu/~jekostas/jekostas.html'>James Kostas</a>, 
              <a href='https://people.cs.umass.edu/~pthomas/'>Philip Thomas</a>
              <br>
              Continual Learning workshop at the Thirty-second Conference on Neural Information Processing Systems (NeurIPS 2018)
          </p>  
     </td>
   </tr>

   <tr>
     <td width="14%"  valign="middle">
            <img src="/images/publications/fgcn.png" alt="FGCN" align="middle" style="width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Fusion Graph Convolutional Networks</paper>
              <br>
              <a href='https://priyeshv.github.io/'>Priyesh Vijayan</a>
              <b>Yash Chandak</b>, 
              <a href='https://www.cse.iitm.ac.in/~miteshk/'>Mitesh Khapra</a>,   
              <a href='https://www.cse.iitm.ac.in/~ravi/'>Balaraman Ravindran</a>
              <br>
              14th International Workshop on Machine Learning with Graphs, 24th ACM SIGKDD Conference on
Knowledge Discovery and Data Mining (KDD 2018).
              <details>
                <summary>Abstract | <a href="https://arxiv.org/abs/1805.12528">Arxiv</a> | <a href="https://github.com/PriyeshV/HOPF">Code</a></summary>            
                  <p class="message">
                     Semi-supervised node classification in attributed graphs, i.e., graphs with node features, involves learning to classify unlabeled nodes given a partially labeled graph. Label predictions are made by jointly modeling the node and its' neighborhood features. State-of-the-art models for node classification on such attributed graphs use differentiable recursive functions that enable aggregation and filtering of neighborhood information from multiple hops. In this work, we analyze the representation capacity of these models to regulate information from multiple hops independently. From our analysis, we conclude that these models despite being powerful, have limited representation capacity to capture multi-hop neighborhood information effectively. Further, we also propose a mathematically motivated, yet simple extension to existing graph convolutional networks (GCNs) which has improved representation capacity. We extensively evaluate the proposed model, F-GCN on eight popular datasets from different domains. F-GCN outperforms the state-of-the-art models for semi-supervised learning on six datasets while being extremely competitive on the other two. 
                  </p>
              </details>
          </p>  
     </td>
   </tr>
      
   <tr>
     <td width="14%"  valign="middle">
            <img src="/images/publications/hopf.png" alt="HOPF" align="middle" style="width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>HOPF: Higher Order Propagation Framework for Deep Collective Classification</paper>
              <br>
              <a href='https://priyeshv.github.io/'>Priyesh Vijayan</a>
              <b>Yash Chandak</b>, 
              <a href='https://www.cse.iitm.ac.in/~miteshk/'>Mitesh Khapra</a>,   
              <a href='https://www.cse.iitm.ac.in/~ravi/'>Balaraman Ravindran</a>
              <br>
              Eighth International Workshop on Statistical Relational AI at the 27th International Joint Conference on
Artificial Intelligence (IJCAI 2018).
              <details>
                <summary>Abstract | <a href="https://arxiv.org/abs/1805.12421">Arxiv</a> | <a href="https://github.com/PriyeshV/HOPF">Code</a></summary>            
                  <p class="message">
                     Given a graph where every node has certain attributes associated with it and some nodes have labels associated with them, Collective Classification (CC) is the task of assigning labels to every unlabeled node using information from the node as well as its neighbors. It is often the case that a node is not only influenced by its immediate neighbors but also by higher order neighbors, multiple hops away. Recent state-of-the-art models for CC learn end-to-end differentiable variations of Weisfeiler-Lehman (WL) kernels to aggregate multi-hop neighborhood information. In this work, we propose a Higher Order Propagation Framework, HOPF, which provides an iterative inference mechanism for these powerful differentiable kernels. Such a combination of classical iterative inference mechanism with recent differentiable kernels allows the framework to learn graph convolutional filters that simultaneously exploit the attribute and label information available in the neighborhood. Further, these iterative differentiable kernels can scale to larger hops beyond the memory limitations of existing differentiable kernels. We also show that existing WL kernel-based models suffer from the problem of Node Information Morphing where the information of the node is morphed or overwhelmed by the information of its neighbors when considering multiple hops. To address this, we propose a specific instantiation of HOPF, called the NIP models, which preserves the node information at every propagation step. The iterative formulation of NIP models further helps in incorporating distant hop information concisely as summaries of the inferred labels. We do an extensive evaluation across 11 datasets from different domains. We show that existing CC models do not provide consistent performance across datasets, while the proposed NIP model with iterative inference is more robust.
                  </p>
              </details>
          </p>  
     </td>
   </tr>
   
</table>

<br>
#### 2015


<table>
   <tr>
     <td width="14%"  valign="middle">
            <img src="/images/publications/human_machine.png" alt="Human-Machine" align="middle" style="width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>On Optimizing Human-Machine Task Assignment</paper>
              <br>
              <a href='https://www.cs.cornell.edu/~andreas/'>Andreas Veit</a>,
              <a href='http://mjwilber.org/'>Michael Wilber</a>,
              <a href='http://www.rajanvaish.com/index.html'>Rajan Vaish</a>,
              <a href='https://tech.cornell.edu/people/serge-belongie/'>Serge Belongie</a>,
              <a href='https://users.soe.ucsc.edu/~davis/'>James Davis</a>,
              <b>Others</b>
              <br>
              The thrid AAAI Conference on Human Computation and Crowdsourcing (wip) (HCOMP 2015).
              <details>
                <summary>Abstract | <a href="https://arxiv.org/pdf/1509.07543.pdf">Arxiv</a> </summary>            
                  <p class="message">
                     When crowdsourcing systems are used in combination with machine inference systems in the real world, they benefit the most when the machine system is deeply integrated with the crowd workers. However, if researchers wish to integrate the crowd with "off-the-shelf" machine classifiers, this deep integration is not always possible. This work explores two strategies to increase accuracy and decrease cost under this setting. First, we show that reordering tasks presented to the human can create a significant accuracy improvement. Further, we show that greedily choosing parameters to maximize machine accuracy is sub-optimal, and joint optimization of the combined system improves performance. 
                  </p>
              </details>
          </p>  
     </td>
   </tr>
</table>
