---
title: "ISLa - Research"
layout: textlay
excerpt: "ISLa Group Research"
sitemap: false
permalink: /research/
---

# Research

Our research group aims at developing methodological and applied research in Artificial Intelligence, Machine Learning and data analysis for intelligent systems.
The code of our project is available at https://github.com/Isla-lab

#### Artificial Intelligence algorithms (Safe Deep Reinforcement Learning) for Autonomous Vehicles
In recent years, Deep Reinforcement Learning (RL) has emerged as a powerful technique to solve complex problems in a variety of applications, reaching and often outperforming classical algorithms and humans. Our research focuses mainly in novel RL methodologies that address the problem of safety, i.e., the application of RL solutions to problems and domains involving interaction with humans, hazardous situations and expensive hardware.

In particular, we propose to exploit DRL to generate a DNN-based real-time controller for the water monitoring drone and mobile robotics.

<p align="center">
    <img src="{{ site.url }}{{ site.baseurl }}/images/research/research1.png" width="55%" height="55%" />   
</p>

*Possible thesis*:
* Design, compare and, evaluate state of the art algorithms in the environments proposed by unity.
* Work on safety-critical domains, designing specific environments and algorithms. 
* Compare machine learning techniques with other artificial intelligence algorithms, to evaluate which one performs better on a specific task.

#### Water Monitoring with autonomous robotic boats

Build and test various high level control and coordination techniques for autonomous robotic boats for monitoring water conditions in lakes and rivers. This is the main research focus of the INTCATCH 2020 project.

<p align="center">
    <img src="{{ site.url }}{{ site.baseurl }}/images/research/research2.png" width="55%" height="55%" />   
</p>

Possible topics: i) intelligent exploration implementation and evaluation of approaches for intelligent water sampling; ii) HRI study of Human Robot Interaction approaches for controlling a team of autonomous boats;


#### Planning under uncertainty and Explainable Planning for Robotic Systems

<p align="center">
    <img src="{{ site.url }}{{ site.baseurl }}/images/research/research3.png" width="55%" height="55%" />   
</p>

Possible topics in this area: i) Planning under uncertainty: find the best possible action given data received from sensors. An example is to decide the speed that a drone should maintain to make sure it will reach the end of a given path with enough battery. Possible techniques include Markov Decision Processes (MDPs), Partialy Observable MDPs, Monte Carlo methods. Another key aspect is safety. Possible thesis can be on Safe Policy Improvement applied to Monte Carlo methods. ii) Explainable planning: devise methods to explain to a human user the decision of an artificial intelligent system is a key requirement for modern AI. Applying this concept to robotic systems is extremely challenging beacuse one must handle the inherent complexity and uncertainty typical of these systems. Possible techniques include logic based methods to planning and decision making (e.g., Satifiability Modulo Theory, Answer Set Programming, etc.).


#### Formal Verification of Deep Neural Networks
DNNs have shown impressive performance in various tasks. However, the vulnerability of these models to adversarial inputs is a well-documented phenomenon observed across various applications. Formal Verification (FV) of DNNs uses mathematical methods to rigorously prove that a neural network meets certain safety and reliability requirements expressed as input-output relationships. Our research group is very active in this topic. We developed ProVe (Corsi et al. 2021) an interval propagation-based method and CountingProVe (Marzari, Corsi et al. 2023) a first randomized-approximated algorithm for the #DNN-Verification problem.

<p align="center">
    <img src="{{ site.url }}{{ site.baseurl }}/images/research/research4.png" width="55%" height="55%" />   
</p>


#### Multi-Robot Coordination, Anomaly Detection and Recovery

Implement and evaluate coordination approaches for Multi-robot systems. Design coordination approaches for robotic agents involved in indoor logistic operations (e.g., pickup and delivery). Test the solution on a widely used simulation environments (ROS + stage) and possibly on real platforms (turtlebot, RB-KAIROS);

<p align="center">
    <img src="{{ site.url }}{{ site.baseurl }}/images/research/research5.png" width="55%" height="55%" />   
</p>