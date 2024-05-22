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

I work as a member of the technical staff at [Cohere](https://cohere.com/). Previously, I worked as a postdoc for [Prof. Emma Brunskill](https://cs.stanford.edu/people/ebrun/) at [Stanford University](https://www.stanford.edu/). 
I received my PhD at the [University of Massachusetts](https://www.umass.edu/), where I was fortunate to be advised by [Prof. Philip Thomas](https://people.cs.umass.edu/~pthomas/).
<br>  
My Resume/CV can be found [here](/docs/Resume.pdf). 

<br>


## Research Interests

Click [here](/publication) for all the publications.


### Formal Reasoning & Decision-Making with Foundation Models

<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">


<tr>
       <td width="14%"  valign="top">
            <img src="/images/publications/web_LEAN.png" alt="lean" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Information Directed Search for Formal Reasoning with Large Language Models</paper>
              <br>  
              <b>Yash Chandak</b>,    
              <a href='https://jonathannlee.com/'>Jonathan N. Lee</a>,
              <a href='https://cs.stanford.edu/people/ebrun/'>Emma Brunskill</a>.
            <br>
       In preparation.
       <br><br>
       Abstract: Formal reasoning tasks are challenging to solve but often there is availability of rich feedback, unlike a scalar feedback in the classical RL setting. How do we combine LLMs and RL to obtain the best of both for long-horizon (formal) reasoning tasks like theorem proving and code generation?   
          </p>  
     </td>
   </tr> 
    
  <tr>
       <td width="14%"  valign="top">
            <img src="/images/publications/web_DPT.png" alt="DPT" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Supervised Pretraining Can Learn In-Context Reinforcement Learning </paper>
              <br>  
              <a href='https://jonathannlee.com/'>Jonathan N. Lee</a>,
              <a href='https://anxie.github.io/'>Annie Xie</a>,
              <a href='https://www.aldopacchiano.ai/'>Aldo Pacchiano</a>,
              <b>Yash Chandak</b>,    
              <a href='https://ai.stanford.edu/~cbfinn/'>Chelsea Finn</a>,
              <a href='https://ofirnachum.github.io/'>Ofir Nachum</a>,
              <a href='https://cs.stanford.edu/people/ebrun/'>Emma Brunskill</a>.
            <br>
            <b>(Spotlight)</b> Thirty-seventh Conference on Neural Information Processing Systems (NeurIPS 2023) | <a href="https://arxiv.org/abs/2306.14892">Arxiv</a>
       <br><br>
       Abstract: Can supervised pre-training provide in-context capabilities to solve decision-making problems? Perhaps surprisingly, drawing formal connections to posterior sampling, in-context interaction with the same model can result in conservative behavior in the offline setting, and also optimistic exploration in the online setting.  
          </p>  
     </td>
  </tr> 
  </table>



### Strategic Data Collection & Reward Design

<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">
     
<tr>
       <td width="14%"  valign="top">
            <img src="/images/publications/web_DIA.png" alt="DIA" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Adaptive Instrument Design for Indirect Experiments</paper>
              <br>  
              <b>Yash Chandak</b>,    
              <a href='https://scholar.google.com/citations?user=yK56jugAAAAJ&hl=en'>Shiv Shankar</a>,
              <a href='https://vsyrgkanis.com/'>Vasilis Syrgkanis</a>,
              <a href='https://cs.stanford.edu/people/ebrun/'>Emma Brunskill</a>.
            <br>
            Twelfth International Conference on Learning Representations (ICLR 2024) | <a href="https://arxiv.org/abs/2312.02438">Arxiv</a>
       <br><br>
       Abstract: In human-AI systems, AI can only be suggestive and not prescriptive about what a human should do (e.g., how should a student interact with LLMs to learn quicker). In such cases, how should AI systems interact strategically to quickly estimate what would have happened had the human complied to its suggestions?  
          </p>  
     </td>
   </tr> 

<tr>
       <td width="14%"  valign="top">
            <img src="/images/publications/web_BARFI.png" alt="BARFI" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Behavior Alignment via Reward Function Optimization</paper>
              <br>  
              <a href='https://dhawgupta.com/'>Dhawal Gupta</a>*,
              <b>Yash Chandak</b>*,    
              <a href='https://scottjordan.github.io/scottjordan/'>Scott Jordan</a>,
              <a href='https://people.cs.umass.edu/~pthomas/'>Philip Thomas</a>,
              <a href='https://people.cs.umass.edu/~bsilva/'>Bruno Castro da Silva</a>.
            *Equal contribution
            <br>
            <b>(Spotlight)</b> Thirty-seventh Conference on Neural Information Processing Systems (NeurIPS 2023) | <a href="https://arxiv.org/abs/2310.19007">Arxiv</a>
       <br><br>
       Abstract: How should we leverage side-information to design reward functions that are dense, yet aligned with a user's goal? We show that the classic approach of reward shaping has several limitations, and propose a new bi-level reward alignment procedure to address the challenges. 
        </p>  
     </td>
  </tr> 
  </table>

<!-- 
### Reinforcement Learning for Non-stationary Environments

<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">
<tr>
     <td width="14%"  valign="top">
            <img src="/images/publications/web_UnO.png" alt="UnO" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
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
             Thirty-fifth Conference on Neural Information Processing Systems (NeurIPS 2021). <a href="https://arxiv.org/abs/2104.12820">[Pdf]</a> 
            <br>
              <font color='red'>Best Paper</font> award at the Conference on Reinforcement Learning and Decision Making (RLDM 2022).
          </p>  
     </td>
   </tr>
   <tr>
     <td width="14%"  valign="top">
            <img src="/images/publications/prognosticator.png" alt="Future" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%"/> 
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
              Thirty-seventh International Conference on Machine Learning (ICML 2020). <a href="https://arxiv.org/abs/2005.08158">[Pdf]</a> 
          </p>  
     </td>
   </tr>

  </table>

 -->



<!-- ## Recent 

- Our papers on (a) Behavior Alignment via Reward Function Optimization, and (b) Supervised Pretraining Can Learn In-Context Reinforcement Learning, got spotlight acceptance at NeurIPS'23.
- Our papers on (a) Representations and Exploration for Deep Reinforcement Learning using Singular Value Decomposition, and (b) Understanding Self-Predictive Learning for Reinforcement Learning, got accepted at ICML'23.
- Our paper on obtaining asymptotically unbiased off-policy policy evaluation when reusing old data in nonstationary environments got accepted at AISTATS'23.
- Our papers on (a) Off-Policy evaluation for action-dependent non-stationary environments, and (b) Factored distributionally robust policies for contextual bandits, got accepted at NeurIPS'22.
- PhD done. Graduated! Thanks to Phil for making my PhD journey amazing!
- RLDM 2022 best paper award for our work on universal off-policy evaluation.
<br><br> -->






