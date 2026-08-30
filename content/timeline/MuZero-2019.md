---
date: 2019-11-19
title: Mastering Atari, Go, chess and shogi by planning with a learned model
img: /images/MuZero-2019.png
---

## Abstract

<figure>
  <img src="/images/MuZero-2019.png" alt="MuZero's performance throughout training in chess, shogi, Go and Atari, matching or exceeding prior algorithms in all four domains" />
</figure>

Constructing agents with planning capabilities has long been one of the main challenges in the pursuit of artificial intelligence. Tree-based planning methods have enjoyed huge success in challenging domains, such as chess and Go, where a perfect simulator is available. However, in real-world problems the dynamics governing the environment are often complex and unknown. In this work we present the MuZero algorithm which, by combining a tree-based search with a learned model, achieves superhuman performance in a range of challenging and visually complex domains, without any knowledge of their underlying dynamics. MuZero learns a model that, when applied iteratively, predicts the quantities most directly relevant to planning: the reward, the action-selection policy, and the value function. When evaluated on 57 different Atari games - the canonical video game environment for testing AI techniques, in which model-based planning approaches have historically struggled - our new algorithm achieved a new state of the art. When evaluated on Go, chess and shogi, without any knowledge of the game rules, MuZero matched the superhuman performance of the AlphaZero algorithm that was supplied with the game rules.

[Paper](https://arxiv.org/pdf/1911.08265)
