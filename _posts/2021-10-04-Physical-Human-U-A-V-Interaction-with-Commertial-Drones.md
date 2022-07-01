---

layout: post
author: past

---

This project uses filtering to estimate forces exerted on a quadrotor and develop a reference trajectoryto track desired motions.

[![quad interaction](/assets/images/admittance_control_conference/chris_quads2.png)](https://youtu.be/Qv7ZBP104V8)


### Project Summary
In this paper, we propose a control scheme that allows generic commercial multirotor Unmanned Aerial Vehicles (UAVs) to infer human intent from physical interaction. 

![control diagram](/assets/images/admittance_control_conference/control_diagram.png)

Humans apply forces by touching it or pulling a nylon string attached to the body frame of the vehicle. The estimations of these forces, obtained via a square root unscented Kalman filter, are used by an admittance controller to generate a reference trajectory such that the vehicle reacts as a desired mass-damper system. 

To track this trajectory, the differential flatness property of the multirotor dynamic model is exploited. This, in fact, allows the generation of any possible kind of input required by the on-board controller supplied by the manufacturer. 
We validate our results experimentally on a Parrot Bebop 2 quadrotor, a commercially available UAV.


![experiment results](/assets/images/admittance_control_conference/exp_results.png)



[Conference Paper](/publications_dir/admittance_control_paper.pdf)

[GitHub](https://github.com/abono3/copuav)
