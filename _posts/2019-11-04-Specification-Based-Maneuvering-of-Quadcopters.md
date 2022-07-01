---

layout: post
author: past

---

Development of a motion planning and task delegation framework that leverages quadrotor dynamics and temporal logic.



[![composite_still](/assets/images/specification_based_conference/composite_still.png)](https://youtu.be/bDOgGxCg0pU)

***A composite image of a quadcopter satisfying a user provided specification (click on image for video***

### Project Summary
In this paper, we study the problem of navigating
quadcopters through a sequence of hoops. 


The specification
may be given directly or indirectly via a linear temporal logic
(LTL) formula. We approach this problem in three phases.


First, we introduce a planner that generates a path through
a given sequence of hoops. 


Second, we augment our planner
to leverage a given specification in linear temporal logic (LTL)
and generate a sequence that satisfies this specification. 


Third,
we implement cross-entropy optimization on this planner to
enhance trajectory performance where quadcopter trajectories
are modified within the solution space to optimize over a cost function. 

![path samples](/assets/images/specification_based_conference/samples_of_all_paths.png)

We implement this planner as a novel interaction modality between users and quadcopters on the Robotarium. Simulation and experimental results are provided.

![still_from_exp_conf](/assets/images/specification_based_conference/spec_based_maneuver_still.png)

[Conference Paper](/publications_dir/specification_paper_2019.pdf)
