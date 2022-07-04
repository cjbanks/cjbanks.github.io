---

layout: post
author: past

---

In this paper, we propose a graph-based search method to optimally allocate tasks to a team of robots given a global task specification. 

[![fire_fighters](/assets/images/multi_agent_task_allocation_conference/fire_fighters_crop.png)](https://youtu.be/4hIinF40V7k)
***Click on the Image for Video***

### Project Summary
In particular, we define these agents as discrete transition systems. In order to allocate tasks to the team of robots, we decompose finite linear temporal logic (LTL) specifications and consider agent specific cost functions. We propose to use the stochastic optimization technique, cross entropy, to optimize over this cost function. 


The multi-agent task allocation cross-entropy (MTAC-E) algorithm is developed to determine both when it is optimal to switch to a new agent to complete a task and minimize the costs associated with individual agent trajectories. 

![cost_optimization](/assets/images/multi_agent_task_allocation_conference/quad_cost_optimization.png)

The proposed algorithm is verified in simulation and experimental results are included.
