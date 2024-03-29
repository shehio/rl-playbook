---
author:
  name: ""
date: 05 Jul 2017
linktitle:
type:
- post
- posts
title: Hindsight Experience Replay
img: /images/HER.png
eventname:
eventlocation:  
weight: 10
---

## Abstract

<figure>
  <img src="/images/HER.png" />
</figure>

Dealing with sparse rewards is one of the biggest challenges in Reinforcement Learning (RL). We present a novel technique called Hindsight Experience Replay which allows sample-efficient learning from rewards which are sparse and binary and therefore avoid the need for complicated reward engineering. It can be combined with an arbitrary off-policy RL algorithm and may be seen as a form of implicit curriculum.

We demonstrate our approach on the task of manipulating objects with a robotic arm. In particular, we run experiments on three different tasks: pushing, sliding, and pick-and-place, in each case using only binary rewards indicating whether or not the task is completed. Our ablation studies show that Hindsight Experience Replay is a crucial ingredient which makes training possible in these challenging environments. We show that our policies trained on a physics simulation can be deployed on a physical robot and successfully complete the task.

[Paper](https://arxiv.org/pdf/1707.01495.pdf)
