---
permalink: "/publication/"
layout: page
title: Publications
sidebar_link: true
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

### 2018

<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">
   <tr>
     <td width="12%"  valign="top">
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
              <!-- [<a href="">Arxiv</a>, <a href="">Code</a>] -->
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
     <td width="12%"  valign="top">
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
              <!-- [<a href="">Arxiv</a>, <a href="">Code</a>] -->
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
     <td width="12%"  valign="top">
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
              [<a href="https://arxiv.org/abs/1805.12528">Arxiv</a>, <a href="https://github.com/PriyeshV/HOPF">Code</a>] 
              <details>
                <summary>Abstract</summary>            
                  <p class="message">
                     Semi-supervised node classification in attributed graphs, i.e., graphs with node features, involves learning to classify unlabeled nodes given a partially labeled graph. Label predictions are made by jointly modeling the node and its' neighborhood features. State-of-the-art models for node classification on such attributed graphs use differentiable recursive functions that enable aggregation and filtering of neighborhood information from multiple hops. In this work, we analyze the representation capacity of these models to regulate information from multiple hops independently. From our analysis, we conclude that these models despite being powerful, have limited representation capacity to capture multi-hop neighborhood information effectively. Further, we also propose a mathematically motivated, yet simple extension to existing graph convolutional networks (GCNs) which has improved representation capacity. We extensively evaluate the proposed model, F-GCN on eight popular datasets from different domains. F-GCN outperforms the state-of-the-art models for semi-supervised learning on six datasets while being extremely competitive on the other two. 
                  </p>
              </details>
          </p>  
     </td>
   </tr>
      
   <tr>
     <td width="12%"  valign="top">
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
              [<a href="https://arxiv.org/abs/1805.12421">Arxiv</a>, <a href="https://github.com/PriyeshV/HOPF">Code</a>] 
              <details>
                <summary>Abstract</summary>            
                  <p class="message">
                     Given a graph where every node has certain attributes associated with it and some nodes have labels associated with them, Collective Classification (CC) is the task of assigning labels to every unlabeled node using information from the node as well as its neighbors. It is often the case that a node is not only influenced by its immediate neighbors but also by higher order neighbors, multiple hops away. Recent state-of-the-art models for CC learn end-to-end differentiable variations of Weisfeiler-Lehman (WL) kernels to aggregate multi-hop neighborhood information. In this work, we propose a Higher Order Propagation Framework, HOPF, which provides an iterative inference mechanism for these powerful differentiable kernels. Such a combination of classical iterative inference mechanism with recent differentiable kernels allows the framework to learn graph convolutional filters that simultaneously exploit the attribute and label information available in the neighborhood. Further, these iterative differentiable kernels can scale to larger hops beyond the memory limitations of existing differentiable kernels. We also show that existing WL kernel-based models suffer from the problem of Node Information Morphing where the information of the node is morphed or overwhelmed by the information of its neighbors when considering multiple hops. To address this, we propose a specific instantiation of HOPF, called the NIP models, which preserves the node information at every propagation step. The iterative formulation of NIP models further helps in incorporating distant hop information concisely as summaries of the inferred labels. We do an extensive evaluation across 11 datasets from different domains. We show that existing CC models do not provide consistent performance across datasets, while the proposed NIP model with iterative inference is more robust.
                  </p>
              </details>
          </p>  
     </td>
   </tr>
   
</table>

### 2015


<table>
   <tr>
     <td width="12%"  valign="top">
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
              [<a href="https://arxiv.org/pdf/1509.07543.pdf">Arxiv</a>] 
              <details>
                <summary>Abstract</summary>            
                  <p class="message">
                     When crowdsourcing systems are used in combination with machine inference systems in the real world, they benefit the most when the machine system is deeply integrated with the crowd workers. However, if researchers wish to integrate the crowd with "off-the-shelf" machine classifiers, this deep integration is not always possible. This work explores two strategies to increase accuracy and decrease cost under this setting. First, we show that reordering tasks presented to the human can create a significant accuracy improvement. Further, we show that greedily choosing parameters to maximize machine accuracy is sub-optimal, and joint optimization of the combined system improves performance. 
                  </p>
              </details>
          </p>  
     </td>
   </tr>
</table>