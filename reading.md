---
layout: page
title:
permalink: /Reading List/
---

<p>
	Below is a reading list I am in the process of compiling for researchers interested in manipulation. Please email me with suggestions for papers to add.
</p>

<!-- ****************************** -->
<h3> Surveys: </h3>
<p>
	<a href="https://www.annualreviews.org/doi/pdf/10.1146/annurev-control-060117-104848"> "Towards Robotic Manipulation," M. Mason (2018)</a>
</p>
<p>
	This paper provides an excellent introduction to robotic manipulation. The paper outlines what manipulation is from several perspectives and provides an interesting comparative perspective on engineering manipulation solutions vs biological evolution. The paper continues to discuss tool use and the key challenges in engineering manipulation. I highly this paper for anyone in the field.
</p>
<!-- ****************************** -->
<h3> Contact Mechanics: </h3>

<p>
	<a href="https://epubs.siam.org/doi/abs/10.1137/S0036144599360110"> "Rigid-Body Dynamics with Friction and Impact," D. Stewart (2000)</a>
</p>
<p>
	I highly recommend this paper if you're interesting in an easy to read introduction to single-point and multi-point rigid-body contact modeling using linear complementarity formulation with time-stepping. Has a lot of detail for numerical implementations and uses Newton restitution model.
</p>

<p>
	<a href="https://pdfs.semanticscholar.org/21f2/85aef8f93d540d7fd80d59e1514d9aabbd13.pdf"> "Time-stepping for three-dimensional rigid body dynamics," M. Anitescu et al. (1999)</a>
</p>
<p>
	An important companion paper to the one mentioned above. Gives a really nice modeling explanation and introduces elastic contact restitution for Poission.
</p>

<!-- ****************************** -->
<h3> Planning Through Contact: </h3>

<p>
	<a href="http://journals.sagepub.com/doi/abs/10.1177/0278364913506757"> "A Direct Method for Trajectory Optimization of Rigid Bodies Through Contact," M. Posa et al. (2014)</a>
</p>
<p>
	A great paper to get into planning through contact with rigid-body dynamics. Formulates the trajectory optimization
  problem through contact, making the LCP constraints explicit in the optimization.
</p>

<p>
	<a href="http://stanford.edu/group/rexlab/papers/variational-ijrr.pdf"> "Contact-Implicit Trajectory Optimization Using Variational Integrators," Z. Manchester et al. (2014)</a>
</p>
<p>
	A great paper to read after reading Michael's paper above. Another instances of explicitly including the LCP constraints for contact in the optimization. This paper introduces higher order	accuracy integration for the contact free motion, allowing bigger steps.
</p>

<p>
	<a href="http://www.roboticsproceedings.org/rss14/p58.pdf"> "In-Hand Manipulation via Motion Cones," N. Chavan-Dafle et al. (2018)</a>
</p>
<p>
	Interesting paper demonstrating in hand manipulation using stable frictional contacts. The formulation shows how to use the environment as an additional finger and computes a sequence of motions for the robot gripper to re-grasp the object in a desired pose. The planner is very fast and the video is very very nice.
</p>

<!-- ****************************** -->
<h3> State Estimation Through Contact: </h3>

<!-- ****************************** -->
<h3> Learning for Manipulation: </h3>

<p>
	<a href="https://arxiv.org/pdf/1809.10790.pdf"> "Deep Object Pose Estimation for Semantic Robotic Grasping of Household Objects," J. Tremblay et al. (2018)</a>
</p>
<p>
	The paper demonstrates the pose tracking of several items. It works remarkably well, even in clutter and during occlusions. The system seems to only be working for 6 objects but returns 6dof poses and is available for download.
</p>

<p>
	<a href="https://rse-lab.cs.washington.edu/papers/se3posenets_icra18.pdf"> "SE3-Pose-Nets: Structured Deep Dynamics Models for Visuomotor Control," A. Byravan et al. (2018)</a>
</p>
<p>
	The paper demonstrates a structured approach to learning visuomotor skills. The novelty is in the masks the network produces, capturing limbs and their motions. This is in contrast to the vast majority of work which does not explicitly reason about limbs and uses either purely sensory data from encoders or images with no masks or mappings to limbs.
</p>

<p>
	<a href="https://arxiv.org/pdf/1803.09956.pdf"> "Learning Synergies between Pushing and Grasping with Self-supervised Deep Reinforcement Learning," A. Zheng et al. (2018)</a>
</p>
<p>
	Paper demonstrating an end to end approach for learning grasp and pick synergies for object picking. The input is an image, the output is a grasp or a pick action. The robot separates objects and picks whatever it can.
</p>

<p>
	<a href="https://arxiv.org/pdf/1808.03246.pdf"> "Augmenting Physical Simulators with Stochastic Neural Networks: Case Study of Planar Pushing and Bouncing," A. Ajay et al. (2018)</a>
</p>
<p>
	Paper demonstrates learning a recurrent network that corrects predictions made by a physics engine, then shows how to use the model for a planar manipulation task. The task is to push a secondary disk to a goal target by pushing on a primary disk.
</p>

<p>
	<a href="https://arxiv.org/pdf/1809.07004.pdf"> "Leveraging Contact Forces for Learning to Grasp," H.  Merzic et al. (2018)</a>
</p>
<p>
	Uses measured contact forces to infer and improve the quality of grasps. They use a RL formulation for the problem and the training is mostly done in simulation. The results seem good but yet to be tested in the real world.
</p>

<p>
	<a href="https://arxiv.org/pdf/1804.05195.pdf"> "Motion-based Object Segmentation based on Dense RGB-D Scene Flow," L. Shao et al. (2018)</a>
</p>
<p>
	Paper shows an interesting approach to segmenting objects moving in a scene by tracking pixel flows. The approach is reminiscent to some of Dieter’s work on SE3 nets for object segmentation. This one is different because the output of the network is not a 6dof pose, rather its masks for objects in the scene.
</p>

<p>
	<a href="https://arxiv.org/pdf/1806.08756.pdf"> "Dense Object Nets: Learning Dense Visual Object Descriptors By and For Robotic Manipulation," P. Florence et al. (2018)</a>
</p>
<p>
	Paper shows how to learn some latent representations for objects that allow for generalization to novel instances of the same object. The approach demonstrates grasping for objects using these features. The paper was well received at CoRL 2018.
</p>

<p>
	<a href="https://arxiv.org/pdf/1809.11169.pdf"> "Propagation Networks for Model-Based Control Under Partial Observation," Y. Li et al. (2018)</a>
</p>
<p>
	Paper shows a nuanced version of interactive networks that allow for multiple force interactions between bodies. The approach is useful for modeling and control of rigid-body dynamics and is a solid contribution to the area.
</p>


<!-- ****************************** -->
<h3> Human Manipulation: </h3>
