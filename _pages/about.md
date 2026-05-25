---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

I am **Xinhui Shan**, a prospective PhD applicant in intelligent robotics. I received my M.Sc. in Robotics, Cognition, and Intelligence from the Technical University of Munich, where my master's thesis investigated reinforcement learning for adaptive quadrupedal locomotion.

I am seeking PhD opportunities in **robot learning, reinforcement learning, and control**. I am particularly interested in developing learning-based controllers that enable robots to adapt robustly in complex physical environments, with applications in locomotion, manipulation, and autonomous navigation.

Alongside robotics, I have applied reinforcement learning, learned dynamics models, and predictive modeling to large-scale dynamic control problems. These experiences strengthen my interest in general AI and control methods for systems operating under changing dynamics.

This page presents the projects that best represent my research experience and technical interests.

## Research Interests

- Robot learning and intelligent robotics
- Reinforcement learning for robot control
- Robot dynamics, motion planning, and control systems
- Sim-to-real transfer, legged locomotion, and robotic manipulation
- Learning-based control and decision-making in dynamic systems

## Research Projects

### Robot Learning and Control

**Adaptive Quadrupedal Locomotion for Robot Based on Reinforcement Learning**<br>
*Master's Thesis, Technical University of Munich | December 2023 - June 2024*

**Problem:** How can a small-scale quadrupedal robot adapt to complex terrains when only limited onboard sensing is available?

**Method:** I constructed Fourier-transform-based state representations from IMU signals and designed a customized PPO-based control policy with task-adaptive rewards for ramps, stairs, and spiral staircases.

**Outcome:** The policy achieved stable adaptive locomotion and converged within 300k training steps, approximately 10x faster than PPO and TD3 baselines.

**Resources:** [arXiv preprint](https://doi.org/10.48550/arXiv.2403.11788)

<!-- MEDIA SLOT: Add a quadruped locomotion figure or video here when provided. -->

**Vision-Based Machine Learning Reaching Task and Sim2Real Applications**<br>
*April 2022 - September 2022 | Munich, Germany*

**Problem:** Learn visual target-reaching behaviors for a 7-DoF KUKA LBR iiwa robot and transfer the policy from simulation to a real platform.

**Method:** I encoded RGB-D observations into compact latent representations with an autoencoder, trained PPO policies in randomized simulated scenes, and applied domain randomization for transfer robustness.

**Outcome:** The learned policy transferred to the real robotic platform and maintained stable target-reaching performance under visual variation and sensor noise.

<!-- MEDIA SLOT: Add a simulated/real KUKA comparison figure or video here when provided. -->

**Dynamic Modeling and Adaptive Sliding Mode Controller Design**<br>
*March 2019 - December 2020 | Changchun, China*

**Problem:** Improve the stability and control performance of an onboard craning manipulator under varying operating conditions.

**Method and Outcome:** I contributed to dynamic modeling and an adaptive sliding mode controller, resulting in a peer-reviewed CPHS 2020 paper.

**Resources:** [Paper](https://doi.org/10.1016/j.ifacol.2021.04.218)

### AI and Learning-Based Control for Dynamic Systems

**World Models and Reinforcement Learning for Dynamic Transportation Systems**<br>
*May 2025 - Present | Leuven, Belgium*

**Problem:** Make long-horizon allocation decisions in a large-scale dynamic system whose network configuration and demand vary over time.

**Method:** I developed a Dyna-style model-based reinforcement learning framework using learned dynamics models and multi-step synthetic rollouts for policy optimization.

**Evaluation Setting:** Large-scale microscopic SUMO environments with non-stationary multimodal demand.

<!-- MEDIA SLOT: Add a simulation overview figure, control diagram, or rollout video here when provided. -->

**Munich City Digital Twin and City Traffic Model Development**<br>
*Student Research Assistant | November 2023 - August 2024 | Munich, Germany*

**Contribution:** In the [Stadt:Up project](https://www.stadtup-online.de/), I contributed to a simulation-based digital twin of central Munich for dynamic scenario analysis and virtual-reality evaluation of cycling behavior.

### Robot Perception and Human-Centered Robotics

**Vision-Based Autonomous Navigation for Obstacle Avoidance**<br>
*October 2022 - March 2023 | Munich, Germany*

**Problem and Method:** I built an aerial obstacle-avoidance system for a Parrot AR Drone 2, combining visual-inertial EKF state estimation, place recognition, keyframe matching, motion planning, and PID flight control.

**Evaluation Setting:** Gazebo simulation and real-world flight experiments.

<!-- MEDIA SLOT: Add a navigation trajectory figure or flight video here when provided. -->

**Deep Learning for Hand Gesture Recognition Based on EMG Signals**<br>
*Master's Seminar, Technical University of Munich | April 2024 - August 2024*

**Contribution:** I reviewed CNN, LSTM, and Transformer approaches to EMG-based hand gesture recognition for myoelectric prosthesis control and participated in EMG signal collection.

## Publications

### Robotics and Control

- `arXiv 2024` **X. Shan**, Y. Huang, Z. Bing, Z. Zhang, X. Yao, K. Huang, and A. Knoll, "[Locomotion Generation for a Rat Robot based on Environmental Changes via Reinforcement Learning](https://doi.org/10.48550/arXiv.2403.11788)." Manuscript in preparation for submission to *IEEE Robotics and Automation Letters*.
- `CPHS 2020` Z. Tang, **X. Shan**, and S. Li, "[Dynamic Modeling and Extension Adaptive Sliding Mode Control of Onboard Craning Manipulator](https://doi.org/10.1016/j.ifacol.2021.04.218)," *3rd IFAC Workshop on Cyber-Physical and Human Systems*, Beijing, China, 2020.

### AI and Learning-Based Control for Dynamic Systems

- `ITSC 2026, Accepted` Y. Yang, C. Roncoli, J. Zhu, **X. Shan**, and X. Yang, "Cross-Region High-Resolution Traffic State Prediction: A Multi-Source Meta-Learning Approach," *IEEE International Conference on Intelligent Transportation Systems*, Naples, Italy, 2026.
- `Under Review` N. Yang, **X. Shan**, T. Guo, I. Yamnenko, and C. Antoniou, "[Few-Shot Adaptation for Detecting New Transport Modes using MAML-Optimized Prototypical Mixture-of-Experts Networks](http://dx.doi.org/10.2139/ssrn.6570251)," submitted to *Information Fusion*.
- `In Preparation` **X. Shan** and C. Roncoli, "TransDyn-RL: World Model-Based Reinforcement Learning for Dynamic Lane Allocation," in preparation for submission to *IEEE Transactions on Intelligent Transportation Systems*.

## Honors and Awards

- *2024*: Master's thesis grade 1.0 (100/100), Technical University of Munich.
- Academic Scholarship (4 times), Jilin University.
- Excellent College Student and Excellent College Student Leader (4 times), Jilin University.
- Third Prize, China Contest in Mathematical Modeling.

## Education

**Technical University of Munich**, Munich, Germany<br>
M.Sc. in Robotics, Cognition, and Intelligence, October 2021 - September 2024<br>
GPA: 2.0 (86/100); Master thesis: *Adaptive Quadrupedal Locomotion for Robot Based on Reinforcement Learning* (Grade: 1.0, 100/100)<br>
Selected coursework: Robotics, Robot Motion Planning, Machine Learning, Computer Vision, Mobile Robotics

**Jilin University**, Changchun, China<br>
B.Eng. in Automation, September 2017 - June 2021<br>
GPA: 88/100 (Top 15%)<br>
Selected coursework: Control Theory, Modern Control Theory, Pattern Recognition, Signals and Systems

## Technical Skills

- **Programming and frameworks:** Python (PyTorch, Pandas, OpenCV, TensorFlow, SciPy), C/C++, C#, ROS, MATLAB, Simulink
- **Tools and platforms:** Gazebo, MuJoCo, SUMO, Unity, RoadRunner, Blender, Docker, Git, Linux, LaTeX
- **Languages:** Mandarin (native), English (proficient), German (intermediate), Dutch (basic)
