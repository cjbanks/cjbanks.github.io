---

layout: post
author: active

---

An online method for cross-entropy sampling is developed, used in multi-agent task allocation.

![online_sim_back](/assets/images/online_ce_experiment_run_simback.png)


### Abstract

We present a task orchestration framework for multi-agent systems utilizing linear temporal logic (LTL) andcross entropy optimization, a stochastic optimization technique. We define task orchestration as a combination of taskdecomposition, allocation and planning for a robot or team of robots given a high-level specification. Specifically, weconsider  tasks  that  are  complex  and  consist  of  environment  constraints,  system  constraints,  or  both,  that  must  besatisfied. We first show this for the single agent case where transition systems for the environment allow tasks to bedeveloped as linear temporal logic (LTL) specifications. Trajectories are then generated via motion primitives for a singlequadcopter and optimized via cross entropy to ensure optimal satisfaction of a cost function. We extend this work to themulti-agent case where a team of homogeneous quadcopters are considered to satisfy an LTL specification. In orderto provide faster computations and initial cost agnostic sampling we formulate the online version of multi-agent taskallocation via cross entropy for tasks specified in temporal logic specifications. The results of this framework are verifiedin simulation and experimentally with a team of quadcopters.

[Journal Paper]()

[GitHub]()

