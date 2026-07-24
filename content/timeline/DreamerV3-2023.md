---
date: 2023-01-10
title: Mastering Diverse Domains through World Models
img: /images/DreamerV3-2023.png
---

## Abstract

<figure>
  <img src="/images/DreamerV3-2023.png" alt="Benchmark summary showing Dreamer with a single unified configuration outperforming tuned expert algorithms across Atari, ProcGen, DMLab, Minecraft, Atari100k, Proprio Control, Visual Control, and BSuite, plus a learning curve of Dreamer collecting diamonds in Minecraft from scratch" />
</figure>

Developing a general algorithm that learns to solve tasks across a wide range of applications has been a fundamental challenge in artificial intelligence. Although current reinforcement learning algorithms can be readily applied to tasks similar to what they have been developed for, configuring them for new application domains requires significant human expertise and experimentation. We present DreamerV3, a general algorithm that outperforms specialized methods across over 150 diverse tasks, with a single configuration. Dreamer learns a model of the environment and improves its behavior by imagining future scenarios. Robustness techniques based on normalization, balancing, and transformations enable stable learning across domains. Applied out of the box, Dreamer is the first algorithm to collect diamonds in Minecraft from scratch without human data or curricula. This achievement has been posed as a significant challenge in artificial intelligence that requires exploring farsighted strategies from pixels and sparse rewards in an open world. Our work allows solving challenging control problems without extensive experimentation, making reinforcement learning broadly applicable.

[Paper](https://arxiv.org/pdf/2301.04104)
