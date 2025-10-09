---
title: Projects
nav_order: 2
---

# Recent Projects

## [CrazySAR](/projects/crazysar)
CrazySAR is a modular aerial robotic system with decentralized control architecture built on the [Crazyflie](https://bitcraze.io) platform. It consists of a collection of Crazyflie 2.1+ quadrotors connected to each other with fixed rods by spherical joints to create an open chain structure. The decentralized control architecture is modeled off of the Graph-Based Modeling and Control of Articulated Robots project, where each quadrotor is treated as an agent and physically connected agents can share state and control information. The rods are equipped with magents to allow for easy reconfiguration of the structure.

## [Inverse Learning based Control](/projects/ilbc)
In many nonlinear control problems, it can be difficult or impossible to derive a mathematical model of the system and thus a model-based control strategy cannot be implemented. In some cases, a linearized model may be available, but the linearization typically only applys to a finite region of atttraction around the equilibrium. In this project, we propose a data-driven approach to expand the region of attraction for a linear feedback controller by learning the inverse dynamics of the system. The learned dynamics are then used to calculate an additional control input to augment the linear feedback controller. Experiments are currently in progress on a Crazyflie 2.1+ quadrotor which demonstrate the effectiveness of the proposed method.

## [Graph-Based Modeling and Control of Articulated Robots](/projects/graph-based)
Extensive research on graph-based dynamics and control of multi-agent systems has successfully demonstrated control of robotic swarms, where each robot is perceived as an independent agent virtually connected by a network topology. The strong advantage of the network control structure lies in the decentralized nature of the control action, which only requires the knowledge of virtually connected agents. We seek to expand the ideas of virtual network constraints to physical constraints on a class of tree-structured robots which we denote as single articulated robotic (SAR) systems. In our proposed framework, each link can be viewed as an agent, and each holonomic constraint connecting links serves as an edge. By following the first principles of Lagrangian dynamics, we derive a consensus-like matrix-differential equation with weighted graph and edge Laplacians for the dynamics of a SAR system. The sufficient condition for the holonomic constraint forces becoming independent to the control inputs is derived. This condition leads to a decentralized leader-follower network control framework for regulating the relative configuration of the robot. Simulation results demonstrate the effectiveness of the proposed control method.

## KTH project?