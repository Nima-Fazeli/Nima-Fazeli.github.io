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
    <a href="http://journals.sagepub.com/doi/abs/10.1177/0278364917698749"
    class="button" style="vertical-align:middle"><span>IJRR </span></a>
    <a href="https://link.springer.com/chapter/10.1007/978-3-319-60916-4_38"
    class="button" style="vertical-align:middle"><span>ISRR </span></a>
  </p>
<!-- Entry 4 -->
  <hr>
  <h3>
    Robotic Pick & Place
  </h3>
  <p>
    <img src="{{site..baseurl }}/assets/contact-1.jpg" alt="Inference1" style="float:right;width:40%;" hspace="25">
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
    <a href="http://journals.sagepub.com/doi/abs/10.1177/0278364917698749"
    class="button" style="vertical-align:middle"><span>IJRR </span></a>
    <a href="https://link.springer.com/chapter/10.1007/978-3-319-60916-4_38"
    class="button" style="vertical-align:middle"><span>ISRR </span></a>
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
		Here are some of my previous projects:
	</p>

</div><!-- /.blurb -->
