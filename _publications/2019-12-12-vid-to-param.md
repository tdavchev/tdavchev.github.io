---
title: "Vid2Param: Modelling of Dynamics Parameters from Video."
collection: publications
permalink: /publication/2019-12-12-vid-to-param
excerpt: 'Videos provide a rich source of information, but it is generally hard to extract dynamical parameters of interest. Inferring those parameters from a video stream would be beneficial for physical reasoning. Robots performing tasks in dynamic environments would benefit greatly from understanding the underlying environment motion, in order to make future predictions and to synthesize effective control policies that use this inductive bias. Online physical reasoning is therefore a fundamental requirement for robust autonomous agents. When the dynamics involves multiple modes (due to contacts or interactions between objects) and sensing must proceed directly from a rich sensory stream such as video, then traditional methods for system identification may not be well suited. We propose an approach wherein fast parameter estimation can be achieved directly from video. We integrate a physically based dynamics model with a recurrent variational autoencoder, by introducing an additional loss to enforce desired constraints. The model, which we call Vid2Param, can be trained entirely in simulation, in an end-to-end manner with domain randomization, to perform online system identification, and make probabilistic forward predictions of parameters of interest. This enables the resulting model to encode parameters such as position, velocity, restitution, air drag and other physical properties of the system. We illustrate the utility of this in physical experiments wherein a PR2 robot with a velocity constrained arm must intercept an unknown bouncing ball with partly occluded vision, by estimating the physical parameters of this ball directly from the video trace after the ball is released.'
date: 2019-12-12
venue: 'IEEE Robotics and Automation Letters'
paperurl: 'http://homepages.inf.ed.ac.uk/ksubr/Files/Papers/ICRA20Vid2Param.pdf'
citation: 'Asenov, M., Burke, M., Angelov, D., Davchev, T., Subr, K. and Ramamoorthy, S., 2019. Vid2Param: Modeling of Dynamics Parameters From Video. <i>IEEE Robotics and Automation Letters</i>, 5(2), pp.414-421.'
---

<a href='http://homepages.inf.ed.ac.uk/ksubr/Files/Papers/ICRA20Vid2Param.pdf'>Download paper here</a>

This work shows how models trained entirely in simulation, in an end-to-end manner can perform online system identification, and make probabilistic forward predictions of parameters of interest in the phyical world.
