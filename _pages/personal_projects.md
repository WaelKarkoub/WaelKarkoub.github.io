---
layout: archive
title: "Personal Projects"
permalink: /personal_projects/
author_profile: true
---

## Robotics Middleware Platform (RMP)

Simplified robot software development: Developed a lightweight Kubernetes-based alternative to ROS, reducing complexity and resource usage while ensuring seamless build and deployment with Bazel. Developed a middleware that extends ZeroMQ capabilities and is being migrated to Zenoh to simplify the codebase even further.

- Python-based containers are ~55 Mb, while a comparable highly optimized ROS container is >500 Mb.
- Developed a CLI to improve developer experience; e.g. remote development and remote testing. Built on top of DevSpace and vCluster.
- Successfully integrated CARLA into the platform to develop autonomous vehicles; Integrated Foxglove to visualize the sensors on the vehicle.

Here's a video of RMP integrated with [Foxglove Studio](https://foxglove.dev/studio) and [CARLA](https://carla.org/):
<span style="display:block;text-align:center">[![IMAGE ALT TEXT](http://img.youtube.com/vi/5gEk5Uad6nI/0.jpg)](http://www.youtube.com/watch?v=5gEk5Uad6nI "RMP Integration with Foxglove and Carla") </span>

Here's a video of RMP Provisioning a development environment in kubernetes:
<span style="display:block;text-align:center">[![IMAGE ALT TEXT](http://img.youtube.com/vi/MJMfHNUb9Og/0.jpg)](http://www.youtube.com/watch?v=MJMfHNUb9Og "RMP Provisioning a Development Environment") </span>

## RL Self-Driving Car

Trained a robot golf cart in Unreal Engine 4 (UE4) to follow paths and speed limits, using an RL model that learns by trial and error. Modeled the cart's real-world behavior for accurate simulation. Built a custom training environment using OpenAI Gym.

- Successfully trained a reinforcement learning agent capable of autonomously navigating a golf cart and meeting pre-set navigational objectives.
- Effectively implemented Deep Deterministic Policy Gradient (DDPG) algorithms using Keras and TensorFlow to refine the agent's decision-making processes.
