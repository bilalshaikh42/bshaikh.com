---
title: Lunar Lander Reinforcement Learning Agent
date: 2021-08-03T17:25:13.778Z
summary: >+
  I trained an agent in the OpenAI Gym LunlarLander-v2 environment
  using  [Double DQN](https://arxiv.org/pdf/1509.06461.pdf),  a Q-learning
  algorithm that uses two deep neural networks to estimate the value of each
  action in a given state.

draft: false
featured: true
tags:
  - personal
  - learning
links: []
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
# Introduction

The [OpenAI Gym](https://gym.openai.com/) provides a set of environments for training
a reinforcement learning agent. For this project, I trained an agent for
the *Lunar-Lander-v2* environment. The environment consists of a model
of a lunar lander that must learn to land on a target landing pad.
The pad is represented by the coordinates $(0,0)$. The lander receives a
reward for approaching the target with a speed of $0$. The lander is
rewarded $100$ points for landing and $-100$ points for crashing. Each
lege that is on the ground is rewarded $10$ points. Using the engine has
a cost of $-0.3$ per use. The lander receives an eight-dimensional
input, consisting of
$[ x, y, \theta, \dot x, \dot y, \dot \theta, l, r]$ where $x$ and $y$
are the coordinates from the landing pad, $\theta$ is the angular
rotation, $\dot z$ represents the derivative of $z$ and $l$ and $r$ are
boolean values $(0/1)$ that represents signal if each leg is on the
ground. The lander has a choicer of four actions:

1.  Do Nothing

2.  Fire Left Enginge

3.  Fire Right Engine

4.  Fire Main Engine

An agent is considered successful if it scores an average of 200 points
or more over the last 100 episodes. Here, I use a Deep-Q Learning algorithm called [Double DQN](https://arxiv.org/pdf/1509.06461.pdf) to train a lander that achieves an average score of 272 over 100 episodes.
