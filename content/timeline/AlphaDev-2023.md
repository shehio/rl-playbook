---
date: 2023-06-07
title: Faster sorting algorithms discovered using deep reinforcement learning
img: /images/AlphaDev-2023.png
---

## Abstract

<figure>
  <img src="/images/AlphaDev-2023.png" alt="The AssemblyGame: AlphaDev receives the current algorithm state and appends an assembly instruction (a), and the algorithm's correctness and latency are computed by comparing outputs against expected outputs over test input sequences to yield the reward (b)." />
</figure>

Fundamental algorithms such as sorting or hashing are used trillions of times on any given day. As demand for computation grows, it has become critical for these algorithms to be as performant as possible. Whereas remarkable progress has been achieved in the past, making further improvements on the efficiency of these routines has proved challenging for both human scientists and computational approaches. Here we show how artificial intelligence can go beyond the current state of the art by discovering hitherto unknown routines. To realize this, we formulated the task of finding a better sorting routine as a single-player game. We then trained a new deep reinforcement learning agent, AlphaDev, to play this game. AlphaDev discovered small sorting algorithms from scratch that outperformed previously known human benchmarks. These algorithms have been integrated into the LLVM standard C++ sort library. This change to this part of the sort library represents the replacement of a component with an algorithm that has been automatically discovered using reinforcement learning. We also present results in extra domains, showcasing the generality of the approach.

[Nature Article](https://www.nature.com/articles/s41586-023-06004-9)
