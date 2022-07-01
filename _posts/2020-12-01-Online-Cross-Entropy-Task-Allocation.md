---

layout: post
author: past

---

An online method for cross-entropy sampling is developed, used in multi-agent task allocation.

[![online_sim_back](/assets/images/online_ce_experiment_run_simback.png)](https://youtu.be/U9OZ_tGr4As)
**Click on the Image for Video**

### Project Summary
This paper presents a task orchestration framework for multiagent systems utilising linear temporal logic (LTL) and cross entropy optimisation, a stochastic optimisation technique used for rare-event sampling. 


We define task orchestration as a combination of task decomposition, allocation and planning for a quadcopter or team of quadcopters given a high level specification. Specifically, we consider tasks that are complex and consist of environment constraints, system constraints, or both, that must be satisfied. 

![transition_system](/assets/images/online_ce_journal/robo_env_product_sys.png)

We first approach motion planning for the single agent case where transition systems for the environment allow tasks to be developed as linear temporal logic (LTL) specifications. Trajectories are then generated via motion primitives for a single quadcopter and optimised via cross entropy to ensure optimal satisfaction of a cost function. We extend this work to the multiagent case where a team of homogeneous quadcopters are considered to satisfy an LTL specification. 

In order to provide faster computations and initial cost-agnostic sampling, we formulate the online version of multi-agent task allocation via cross entropy for tasks specified in LTL specifications. The results of this framework are verified in simulation and experimentally with a team of quadcopters.

![still_from_exp_journal](/assets/images/online_ce_journal/still_from_exp_journal.png)

[Journal Paper](/publications_dir/ltl_cross_entropy_2022.pdf)

[comment]:<>([GitHub]())

