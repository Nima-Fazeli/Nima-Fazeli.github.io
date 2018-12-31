---
layout: default
title: Research
permalink: Research.html
---

<div class="blurb">
  <!-- PhD -->
  <h2>
    PhD Research:
  </h2>

  <p>
		I work on <strong>Inference</strong>, <strong>Modeling/Simulation</strong>,
		<strong>Control</strong>, and <strong>Learning</strong> applied to
		<strong>Robotic Manipulation</strong>.
		I am interested in the complex and exciting world of physical interactions,
		these interactions are fundamental to the utility of real-world agents. Physical
		interactions are complex because they are <strong>hybrid</strong>, which means
		that the dynamics of the robot change as it comes into contact and whether the
		type of contact is permitted to stick or slide. These interactions are also
		<strong>difficult to model</strong> because of the complex nature of frictional
		contact. Though contact is complex, it provides us with a wealth of information
		which we can use to make <strong>inferences</strong> about the world.
	</p>

  <p>
		I work on developing <strong>algorithms</strong> and
		<strong>models</strong> that allow robots to intelligently and autonomously
		interact and learn from their environment. I have worked on both
		<strong>model-based</strong> and <strong>machine learning</strong> approaches
		and believe there is a world in which we can combine our knowledge of physics
		and learning approaches to garner the best of both worlds.
	</p>

  <p>
		Here are some of the projects I have worked on:
	</p>
<!-- Entry 1 -->
  <hr>
  <h3>
    Inferring robot parameters & contact forces during frictional interactions
  </h3>
  <p>
		<img src="{{site..baseurl }}/assets/inference_1.jpg" alt="Inference1" style="float:right;width:40%;" hspace="25" vspace="50">
	</p>
  <p>
		Let's assume we have a robotic system making contact with the
		environment, can we make inferences about the physical properties
		(such as masses, inertias, and contact parameters) of the robotic system? Can we
		also make inferences about the contact forces from the interaction?
	</p>
  <p>
		In this project, I developed a mathematical framework that i) tells
		us explicitly what parameters/forces are identifiable, and ii) provides
		a formulation to compute these quantities given a time-series of observations,
		under the assumption of rigid-body frictional interactions.
	</p>
  <p>
    <a href="https://link.springer.com/chapter/10.1007/978-3-319-60916-4_38"
    class="button" style="vertical-align:middle"><span>ISRR 2015</span></a>
		<a href="http://journals.sagepub.com/doi/abs/10.1177/0278364917698749"
		class="button" style="vertical-align:middle"><span>IJRR 2017</span></a>
  </p>
<!-- Entry 2 -->
  <hr>
  <h3>
    Rigid-Body Contact Modeling: Identification, Evaluation, & Comparison
  </h3>
  <p>
    <img src="{{site..baseurl }}/assets/contact-1.jpg" alt="Inference1" style="float:right;width:40%;" hspace="25">
  </p>
  <p>
    Rigid-body contact models are extremely important to predicting, planning,
    and control of robotic interactions. An important lesson we learned during the
    parameter and force identification project was the sensitivity to the model
    we used. We decided to compare 6 commonly used rigid-body contact models using
    the time-stepping complementarity formulation.
  </p>
  <p>
    In this project, I developed a principled formulation for contact model parameter
    estimation using the Energy Ellipse. I then compared the performance of the models
    on a data-set I collected for planar impact (publicly available). I showed the
    issues and limitations of these models in general for contact and impact outcome
    prediction and demonstrated the upper bound performance for this specific task.
  </p>
  <p>
    <img src="{{site..baseurl }}/assets/pushing.jpg" alt="Inference1" style="float:right;width:40%;" hspace="25">
  </p>
  <p>
    I was also involved in the collection of the largest experimental planar pushing
    data-set available in robotics. In this project, we collected planar pushing data
    for a wide variety of interactions and objects which has found great utility in
    the community for model learning, validation, and control.
  <p>
    <a href="https://ieeexplore.ieee.org/document/7989389/#full-text-section"
    class="button" style="vertical-align:middle"><span>ICRA 2017</span></a>
    <a href="https://arxiv.org/abs/1710.04979"
    class="button" style="vertical-align:middle"><span>ISRR 2017</span></a>
    <a href="https://ieeexplore.ieee.org/abstract/document/7758091/"
    class="button" style="vertical-align:middle"><span>IROS 2016</span></a>
  </p>
<!-- Entry 3 -->
  <hr>
  <h3>
    Rigid-Body Contact Modeling: Learning
  </h3>
  <p>
    <img src="{{site..baseurl }}/assets/learning.jpg" alt="Inference1" style="float:right;width:40%;" hspace="25">
  </p>
  <p>
    In building computationally efficient contact models, we are forced to make assumptions that work to the detriment of precision. Further, we cannot observe or model certain details that additionally affect fidelity. In these projects, we explored the use of data-driven and data-augmented models for contact interactions. The first figure shows the 3 fold improvement in performance over the state-of-the-art models if we combine them with data-driven models.
  </p>
  <p>
    <img src="{{site..baseurl }}/assets/teaser-low.jpg" alt="Inference1" style="float:right;width:40%;" hspace="25">
  </p>
  <p>
    In the second figure, the robot learns a rich physics model of the contact interaction between the two disks and the surface. It then uses this model to perform model-predictive control to push the second disk to a goal using the first disk. This task is an example of a difficult planar manipulation problem with many hybrid modes for which analytical models struggle.
  </p>
  <p>
    <a href="https://arxiv.org/abs/1710.05947"
    class="button" style="vertical-align:middle"><span>CoRL 2017</span></a>
    <a href="https://arxiv.org/abs/1808.03246"
    class="button" style="vertical-align:middle"><span>arXiv 2018</span></a>
  </p>
<!-- Entry 4 -->
  <hr>
  <h3>
    Robotic Pick & Place
  </h3>
  <p>
    <img src="{{site..baseurl }}/assets/ARC_w_background.png" alt="arc1" style="float:right;width:40%;" hspace="25">
  </p>
  <p>
    An important challenge in warehouse automation is automating the process of finding and moving objects desired objects from one place to another. We developed an autonomous system that does exactly this and competed in the Amazon Robotics Challenge (2015-2017), with consistent top 3 placements and winning 1st place in stowing in 2017.
  </p>
  <p>
    The key challenge here is that the robot does not know what the majority of objects are prior to interaction. As such, it needs to understand which objects to go for, and which modality of manipulation it needs to imploy for success. Watch our video for more information.
  </p>
  <p>
    <a href="https://arxiv.org/abs/1604.03639"
    class="button" style="vertical-align:middle"><span>arXiv 2015</span></a>
    <a href="https://ieeexplore.ieee.org/abstract/document/8461044/"
    class="button" style="vertical-align:middle"><span>ICRA 2018</span></a>
  </p>

  <!-- Masters -->
  <hr>
  <h2>
    Masters Research:
  </h2>

  <p>
		During my masters, I worked on <strong>Inference</strong>, <strong>Modeling/Simulation</strong>,
		<strong>Control</strong>, and <strong>Learning</strong> applied to the
		<strong>Human Cardiovascular System</strong> and <strong>pharmacodynamics/pharmacokinetics</strong>.
		Modeling these systems is particularly challenging but has potentially large impact in disease diagnosis and preventative medicine.
	</p>

  <p>
		<strong>System identification</strong> and <strong>machine learning</strong> are important tools that enable us to predict and infer diseases and are critical to diagnosis. These tools enable detection of abnormalities that are central to diagnosis and preventative care.
	</p>

  <p>
		Here are some of my previous projects:
	</p>
  <hr>
  <h3>
    Estimating Cardiac Output and Peripheral Resistance
  </h3>
  <p>
    <img src="{{site..baseurl }}/assets/cardiac-1.jpg" alt="Inference1" style="float:right;width:40%;" hspace="25" vspace="50">
  </p>
  <p>
    One model for the human arterial tree is a simple lumped RC network, where the heart acts as a voltage source and the arterial tree acts as a capacitor/resistor. In this project, assuming that this model holds, we estimate the cardiac output of the heart and the peripheral resistance provided by the arterial tree using in-vivo measurements from swine.
  </p>
  <p>
    In particular, in this study we showed how using a square-wave as the voltage source for the heart does a better job of estimating the cardiac output and provided a formulation for the estimation of the parameters and cardiac output.
  </p>
  <p>
    <a href="https://www.frontiersin.org/articles/10.3389/fphys.2012.00298/full"
    class="button" style="vertical-align:middle"><span>Frontiers 2012</span></a>
  </p>
<!-- Entry 2 -->
  <hr>
  <h3>
    Cardiovascular Modeling and System Identification
  </h3>
  <p>
    <img src="{{site..baseurl }}/assets/cardiac-1.jpg" alt="Inference1" style="float:right;width:40%;" hspace="25" vspace="50">
  </p>
  <p>
    The Tube-Load (TL) model is a well established and relatively complex approximation for the human cardiovascular system. In this sequence of studies, we investigated the fidelity and identifiability of these models on first swine, then humans. In particular, we showed that these models are effective in predicting peripheral and central blood pressures and can reliably estimate the time required for a blood pressure wave to propagate along the upper or lower body conduits.
  </p>
  <p>
    These studies laid the foundation to future work in which we used these models to detect anomalous stiffness or delay in wave propagation that can be indicators of cardiac health.
  </p>
  <p>
    <a href="https://ieeexplore.ieee.org/abstract/document/6579924"
    class="button" style="vertical-align:middle"><span>ACC 2013</span></a>
    <a href="https://link.springer.com/article/10.1007/s11517-014-1185-3"
    class="button" style="vertical-align:middle"><span>MBEC 2014</span></a>
  </p>
  <!-- Entry 3 -->
  <hr>
  <h3>
    Central Aortic Blood Pressure Wave-Form Estimation
  </h3>
  <p>
    <img src="{{site..baseurl }}/assets/cardiac-1.jpg" alt="Inference1" style="float:right;width:40%;" hspace="25" vspace="50">
  </p>
  <p>
    Given the fidelity of the TL model in representing wave propagation in the human arterial, we looked at ways in which we can leverage it for diagnostics and preventative care. In the first set of studies, we investigate the blind recovery of the central aortic blood pressure from two peripheral blood pressure measurements using these models. We showed that it is possible to fully identify the TL model parameters and recover the central BP with high fidelity.
  </p>
  <p>
    The measurements utilized in these studies was invasive and entirely dependent on the frequency content of the waves generated by the heart. We showed that these waveforms, previously measured invasively, are recoverable from oscillations in a blood pressure cuff. We also showed the theoretic possibility of exciting the arterial tree with the cuffs to super-impose waves onto the BP to recover higher fidelity models.
  </p>
  <p>
    <a href="https://ieeexplore.ieee.org/abstract/document/6579924"
    class="button" style="vertical-align:middle"><span>ACC 2013</span></a>
    <a href="https://link.springer.com/article/10.1007/s11517-014-1185-3"
    class="button" style="vertical-align:middle"><span>MBEC 2014</span></a>
  </p>
  <!-- Entry 4 -->
  <hr>
  <h3>
    Pharmacodynamics/pharmacokinetics of Diabetes in Humans
  </h3>
  <p>
    <img src="{{site..baseurl }}/assets/cardiac-1.jpg" alt="Inference1" style="float:right;width:40%;" hspace="25" vspace="50">
  </p>
  <p>
    Pharmacodynamics/pharmacokinetics describe the way in which medication and its effects propagate through the body. In particular, they relate the dose and time of dosage to the propagation and concentration of the medication in the body. Further, they model the effects of the medication on various end-point measures. For example, patients with diabetes consume a dosage of insulin that then affects several end-point responses.
  </p>
  <p>
    In this study, we proposed a novel method to derive data-driven model of pharmacological systems that is built upon information fusion of endpoint responses. We show the system's identifiability by analyzing a relation between endpoint responses and demonstrate that it is fully identifiable in case all the responses involve effect compartments. We demonstrate the efficacy of the method on several benchmark pharmacological modeling problems. This approach is an important step towards tailoring drug dose to a patients physiology.
  </p>
  <p>
    <a href="https://www.sciencedirect.com/science/article/pii/S0010482515000888"
    class="button" style="vertical-align:middle"><span>CBME 2015</span></a>
  </p>

</div><!-- /.blurb -->
