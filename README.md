# Reinforcement Learning for Autonomous navigation of UAVs
This repository contains the <b>simulation source code</b> for implementing reinforcement learning aglorithms for autonomous navigation of ardone in indoor environments. <b>Gazebo</b> is the simulated environment that is used here.
## Q-Learning.py
Autonomous Navigation of UAV using Q-Learning (Reinforcement Learning). 
- State: <b>Discrete</b>
- Action: <b>Discrete</b>
- Action space: <b>5x5 grid space.</b>

<b>Indoor Path Planning and Navigation</b> of an Unmanned Aerial Vehicle (UAV) based on <b>PID + Q-Learning algorithm (Reinforcement Learning)</b>. The quadrotor maneuvers towards the goal point, along the uniform grid distribution in the gazebo simulation environment(<strong>discrete action space</strong>) based on the specified reward policy, backed by the simple position based PID controller.

This project was developed at the <a href="https://sites.google.com/site/compintellab/home/uavla"><b>Advanced Flight Simulation(AFS) Laboratory, IISc, Bangalore</b></a>.
<p align= "center">
<img src="Q-Learning/drone_qlearning.gif/">
</p>

### Dependencies & Packages:
- <b><a href="http://releases.ubuntu.com/16.04/">Ubuntu 16.04</a></b> 
- <b><a href="http://wiki.ros.org/kinetic">ROS Kinetic</a></b>
- <b><a href="http://gazebosim.org/">Gazebo 7</a></b>
- <b><a href="https://github.com/AutonomyLab/ardrone_autonomy">ArDrone Autonomy ROS Package</a></b>
- <b><a href="https://gym.openai.com/docs/">gym: 0.9.3</a></b>
- <b><a href="https://www.tensorflow.org/install/">TensorFLow 1.1.0 (preferrable with GPU support)</a></b>
- <b>Python: 2.7</b>

### Reference:  
- Pham, Huy X., et al. <b><a href="https://arxiv.org/abs/1801.05086">Autonomous uav navigation using reinforcement learning.</a></b> arXiv preprint arXiv:1801.05086 (2018).
- Mnih, Volodymyr, et al. <a href="https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf"><b>Human-level control through deep reinforcement learning.</b></a> Nature 518.7540 (2015)

**<a href="https://goo.gl/zKNQdW">Project Video</a>**

## DDPG.py 
Deep Deterministic Policy Gradient algorithm is used for autonomous navigation of UAV from start to goal position. This is applicable for continuous action-space domain. (Under development!)

### Collaborator(s):
**<a href="https://github.com/ioarun">Arun Kumar</a>**
