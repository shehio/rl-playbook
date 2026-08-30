---
date: 2023-01-10
title: Mastering Diverse Domains through World Models
img: /images/DreamerV3-2023.png
---

## Abstract

<figure>
  <img src="/images/DreamerV3-2023.png" alt="Benchmark summary showing Dreamer with a single unified configuration outperforming tuned expert algorithms across Atari, ProcGen, DMLab, Minecraft, Atari100k, Proprio Control, Visual Control, and BSuite, plus a learning curve of Dreamer collecting diamonds in Minecraft from scratch" />
</figure>

General intelligence requires solving tasks across many domains. Current reinforcement learning algorithms carry this potential but are held back by the resources and knowledge required to tune them for new tasks. We present DreamerV3, a general and scalable algorithm based on world models that outperforms previous approaches across a wide range of domains with fixed hyperparameters. These domains include continuous and discrete actions, visual and low-dimensional inputs, 2D and 3D worlds, different data budgets, reward frequencies, and reward scales. We observe favorable scaling properties of DreamerV3, with larger models directly translating to higher data-efficiency and final performance. Applied out of the box, DreamerV3 is the first algorithm to collect diamonds in Minecraft from scratch without human data or curricula, a long-standing challenge in artificial intelligence. Our general algorithm makes reinforcement learning broadly applicable and allows scaling to hard decision-making problems.

[Paper](https://arxiv.org/abs/2301.04104v1)
