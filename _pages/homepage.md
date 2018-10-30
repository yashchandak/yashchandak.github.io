---
layout: page
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

p {
    padding: 0;
    margin: 0;
}
</style>


<br>

I'm a second year MS/PhD student at the [University of Massachusetts Amherst](https://www.umass.edu/). I am also a member of the [Autonomous Learning Lab (ALL)](http://www-all.cs.umass.edu/) and am fortunate to be advised by [Prof. Philip Thomas](https://people.cs.umass.edu/~pthomas/).
My primary interest is in **continual learning**, a branch of Artificial Intelligence, which aims at teaching machines
new concepts over time. My research is mostly at the intersection of reinforcement learning,
optimization, and machine learning. I enjoy reading and looking out for inspirations from neuroscience as well.
<br><br>

I completed my B.Tech in Computer Science at [VIT University](http://chennai.vit.ac.in/) in 2017, where [Prof. Nithya Darisini](https://www.researchgate.net/scientific-contributions/2046556969_PS_Nithya_Darisini) was my mentor. I was also fortunate to spend most of my senior year at [IIT-Madras](https://www.iitm.ac.in) under the guidance of
[Prof. B. Ravindran](https://www.cse.iitm.ac.in/~ravi/). In my junior year, I had great learning experiences at the Indian [Defence Research and Development Organization(IRDE, DRDO)](https://www.drdo.gov.in/drdo/labs1/IRDE/English/indexnew.jsp?pg=homepage.jsp)
under Dr. J.P. Singh and later at the [University of Technology, Troyes, France](http://www.utt.fr/en/index.html) under [Prof. Babiga Birregah](https://scholar.google.com/citations?user=qHEWWZ8AAAAJ&hl=en).
During my sophomore days, I was introduced to machine learning research by
[Prof. James Davis](https://users.soe.ucsc.edu/~davis/), UCSC, and [Rajan Vaish](http://www.rajanvaish.com), Stanford, through their large-scale research initiative:
[Aspiring Researcher Challenge](https://aspiringresearchers.soe.ucsc.edu/).
Before that, I was a national level basketball player in India and used to play all day everyday.


<br><br>
## Recent

- Interned at Adobe Research under [Dr. Georgios Theocharous](https://research.adobe.com/person/georgios-theocharous/) during Summer 2018.  

<br><br>

## Publications


#### 2018

<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">
   <tr>
     <td width="14%"  valign="top">
            <img src="/images/publications/dynamic_action.png" alt="dynamic_actions" align="top" style="width: 80%; margin:0px 10px; border-radius:0%"/> 
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
              (Under review)
              <details>
                <summary>Abstract</summary>            
                  <p class="message">
                    Reinforcement learning has been successfully applied to many sequential decision making problems, where the set of possible actions (possible decisions) is fixed. However, in many real-world settings, the set of possible actions can change over time.  We present a model-free method to continually adapt to a dynamic set of possible actions. We show how a policy can be decomposed into an internal policy that acts in a space of action representations and a reward-independent component that transforms these representations into actual actions.  These representations not only make the internal policy parameterization invariant to the cardinality of the action set, but also improve generalization by allowing the agent to infer the outcomes of actions similar to actions already taken. We provide an algorithm to autonomously adapt to this dynamic action set by exploiting structure in the space of actions using supervised learning while learning the internal policy using policy gradient.  The efficacy of the proposed method is demonstrated on large-scale real-world continual learning problems. 
                  </p>
              </details>
          </p>  
     </td>
   </tr>

   <tr>
     <td width="14%"  valign="top">
            <img src="/images/publications/action_rep.png" alt="action_representations" align="top" style="width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="top" width="85%">
          <p>
              <paper>Improving Generalization by Learning Action Representations for Reinforcement Learning</paper>
              <br>
              <b>Yash Chandak</b>, 
              <a href='https://research.adobe.com/person/georgios-theocharous/'>Georgios Theocharous</a>,   
              <a href='https://people.cs.umass.edu/~jekostas/jekostas.html'>James Kostas</a>, 
              <a href='https://people.cs.umass.edu/~pthomas/'>Philip Thomas</a>
              <br>
              (Under review)
              <details>
                <summary>Abstract</summary>            
                  <p class="message">
                    Most  model-free  reinforcement  learning  methods  leverage state representations (embeddings) for generalization but either  ignore  structure  in  the  space  of  actions  or  assume the  structure  is  provided a  priori. We  show  how  a  policy can  be  decomposed  into  a  component  that  acts  in  a  lower-dimensional  space  of  action  representations  and  a  component that transforms these representations into actual actions. These representations help to improve generalization by allowing the agent to infer the outcomes of actions similar to actions already taken. We provide an algorithm, along with a  proof  of  its  convergence,  to  both  learn  and  use  these  action representations efficiently. The efficacy of the proposed method is demonstrated on large-scale real-world problems.
                  </p>
              </details>
          </p>  
     </td>
   </tr>

   <tr>
     <td width="14%"  valign="top">
            <img src="/images/publications/fgcn.png" alt="FGCN" align="top" style="width: 80%; margin:0px 10px; border-radius:0%"/> 
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
     <td width="14%"  valign="top">
            <img src="/images/publications/hopf.png" alt="HOPF" align="top" style="width: 80%; margin:0px 10px; border-radius:0%"/> 
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

#### 2015


<table>
   <tr>
     <td width="14%"  valign="top">
            <img src="/images/publications/human_machine.png" alt="Human-Machine" align="top" style="width: 80%; margin:0px 10px; border-radius:0%"/> 
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

<br><br>

## Courses

- [CS 689: Machine Learning](http://openscholar.cs.umass.edu/marlin/classes/compsci-689-machine-learning) 
- [CS 650: Applied Information Theory](https://people.cs.umass.edu/~arya/courses/650/CS650-2016.html)
- [CS 611: Advanced Algorithms](https://people.cs.umass.edu/~ramesh/Site/TEACHING.html)
- [MATH 645: ODEs and Dynamical Systems](http://people.math.umass.edu/~dobson/Math645/index.html)
- [CS 6700: Reinforcement Learning](https://www.cse.iitm.ac.in/~ravi/teaching.html)
- [CS 7015: Deep Learning](https://www.cse.iitm.ac.in/~miteshk/CS7015.html)


<br><br>
## Lab Talks




<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">
   <tr>
     <td width="9%"  valign="top">
            <img src="/images/talks/action_rep.png" alt="action_rep" align="top" style="width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="middle" width="85%">
          <p>
            <b>Improving Generalization by Learning
 Action Representations for Reinforcement Learning.</b>
            <br>
            <a href='http://www-all.cs.umass.edu/'>Autonomous Learning Lab</a>, UMass, 2018. [<a href='https://docs.google.com/presentation/d/1g8v-8Bje6WhUAjcZ4I46gFmoo5thAe4rautrQ3o0gMY/edit?usp=sharing'>Slides</a>]
          </p>  
     </td>
   </tr>
   
   <tr>
     <td width="7%"  valign="top">
            <img src="/images/talks/zap.png" alt="ZapQ" align="top" style="width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="middle" width="85%">
          <p>
            <b>Faster convergence for Q-Learning using Zap-Q.</b>
            <br>
            <a href='http://www-all.cs.umass.edu/'>Autonomous Learning Lab</a>, UMass, 2017. [<a href='https://docs.google.com/presentation/d/1kczu1I8HDtOf6VI8rBHlJ9v4w2NDzFbBf8oqo9_iEBQ/edit?usp=sharing'>Slides</a>]
          </p>  
     </td>
   </tr>

   <tr>
     <td width="7%"  valign="top">
            <img src="/images/talks/talk_lifelong.png" alt="talk_lifelong" align="top" style="width: 80%; margin:0px 10px; border-radius:0%"/> 
     </td>
     <td valign="middle" width="85%">
          <p>
            <b>Life-long learning, overcoming catastrophic forgetting in Neural Netowrks.</b>
            <br>
            <a href='http://rise.cse.iitm.ac.in/'>RISE lab</a>, IIT-Madras, 2017. [<a href='https://docs.google.com/presentation/d/1gcaM2Q6wfpQ4da8KTaCOFaEBpkjTyd_8XJHpygSLF58/edit?usp=sharing'>Slides</a>]
          </p>  
     </td>
   </tr>      
</table>

