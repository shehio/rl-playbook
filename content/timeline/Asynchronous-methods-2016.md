---
author:
  name: ""
date: 04 Feb 2016
linktitle:
type:
- post
- posts
title: Asynchronous Methods for Deep Reinforcement Learning
img: /images/Asynchronous-methods.png
eventname:
eventlocation:  
weight: 10
---

## Abstract

<figure>
  <img src="/images/Asynchronous-methods.png" />
</figure>

We propose a conceptually simple and lightweight framework for deep reinforcement learning that uses asynchronous gradient descent for optimization of deep neural network controllers. We present asynchronous variants of four standard reinforcement learning algorithms and show that parallel actor-learners have a stabilizing effect on training allowing all four methods to successfully train neural network controllers. The best performing method, an asynchronous variant of actor-critic, surpasses the current state-of-the-art on the Atari domain while training for half the time on a single multi-core CPU instead of a GPU. Furthermore, we show that asynchronous actor-critic succeeds on a wide variety of continuous motor control problems as well as on a new task of navigating random 3D mazes using a visual input.

[Paper](https://arxiv.org/pdf/1602.01783.pdf)
