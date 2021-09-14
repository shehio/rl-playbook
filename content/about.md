---
title: About
---

#### Contents
| [Why](#why) | \| [What](#what) | \| [How](#how) | \| [How I learned RL](#how-i-learned-rl) |
| --- | --- | ---- | --- |

---

## Why?

RL is a machine learning paradigm that seeks to make optimal decisions by studying sequences of correlated events. In the 20th century, AI researchers had studied RL for decades but to no avail.

Committed researchers believed that RL could one day bring us closer to [Artificial General Intelligence](https://en.wikipedia.org/wiki/Artificial_general_intelligence), i.e., creating intelligent agents capable of understanding or learning any intellectual task. In short, these computer programs would pass the well-known [Turing test](https://en.wikipedia.org/wiki/Turing_test).

Although RL didn’t seem to be a promising field of research, true believers never lost sight. More importantly, they never lost hope. Only recently, fueled by modern advances in [deep learning](https://en.wikipedia.org/wiki/Deep_learning), RL has successfully taken off. It has tackled many challenges that were deemed to be decades out of reach. Nowadays, it still seems to be on a trajectory to change the world.

In 2013, computer programs employing RL  were able to outperform humans in Atari games. In 2016, Alpha Go, a computer program, beat Lee Seedol, the 18 times world champion. Other wins also included beating pro players in modern games like Poker, Dota, and Starcraft.

These achievements didn’t go unnoticed, with keen researchers featured in various articles in top computer science conferences and most prestigious journals like [Nature](https://www.nature.com/) and [Science](https://www.science.org/).

Games have provided the perfect test environment for different RL algorithms, although researchers have since taken RL to more practical uses. RL shines in solving problems related to robotics, exploration rovers, and of course, self-driving cars. Moreover, it’s used in bid optimization for online ad auctions and building world-class recommenders for your next song or movie.

---

## What?

This website presents a compiled list of research papers and resources to describe the evolution of RL algorithms over time. It’s a resource meant for novice researchers and hobbyists to learn more about breakthroughs in RL throughout the years.

---

## How?

Reinforcement Learning is a branch of machine learning that studies optimal decision-making to maximize a reward function (the equivalent of winning a game). Different algorithms attempt to maximize the reward differently, either by maximizing the value function, value-action function, policy, or a combination.

RL can be model-based, where the algorithm tries to figure out the transitions of the environment or model-free, where the algorithm doesn’t care about learning the environment; it just cares about maximizing a reward function or reaching a near-optimal policy.

Many RL problems are modeled as [Markovian Decision Processes(MDPs)](https://en.wikipedia.org/wiki/Markov_decision_process), which are mostly partially observed. It also leverages [dynamic programming](https://en.wikipedia.org/wiki/Dynamic_programming), [Monte Carlo simulations](https://en.wikipedia.org/wiki/Monte_Carlo_method), and of course, [neural networks](https://en.wikipedia.org/wiki/Artificial_neural_network).

In his seminal [reference](http://incompleteideas.net/book/the-book-2nd.html), [Richard Sutton](https://en.wikipedia.org/wiki/Richard_S._Sutton) writes: “Almost all reinforcement learning algorithms involve estimating value functions.”

---

## How I Learned RL

When I graduated in the early 2010s, I lost hope in machine learning. I perceived different papers as presenting micro-models that fit particular use-cases and only feature carefully curated samples in their results. There’s no way this was going to blow out to full-blown [Artificial General Intelligence](https://en.wikipedia.org/wiki/Artificial_general_intelligence), I thought. 

In 2015, Deep Mind [Now part of Google] published how it created an algorithm that has reached human-level control in playing Atari games just from raw pixels. This was a whole different level of intelligence. A year later, Deep Mind’s creation Alpha-Go beat Lee Sedol in Go, an achievement that was thought to be decades away.

Now, this got me hooked again.

In 2018, I became interested in RL. I read [Sutton-Barto](http://incompleteideas.net/book/the-book-2nd.html), the most widely-known ref, a couple of times and implemented many of the algorithms it covered. I started with writing a family of algorithms called dynamic programming like policy-iteration, value-iteration. I then moved to some trivial problems like finding optimal paths in uneven terrains using Monte-Carlo simulations.

I then worked on creating artificially intelligent agents to play video games. Inspired by [Karpathy](https://twitter.com/karpathy), I leveraged neural networks and worked on a family of algorithms called [policy gradients](https://spinningup.openai.com/en/latest/algorithms/vpg.html). These algorithms try to maximize the actions that have “worked” (yielded a big reward) in the past. As any calculus student would tell you, they move in the direction of the gradient.

Among my practical endeavors, I needed to have a solid theoretical foundation. I needed to study more of the MDPs, Bellman equation, and many proofs.  I watched lectures from top-researchers like David Silver of UCL and Emma Brunskill of Stanford.

At that time, I directed a book club in the applied mathematics department at the University of Washington. For a couple of quarters, we decided to learn more about RL and [GANs](https://en.wikipedia.org/wiki/Generative_adversarial_network). This book club allowed me to read more exciting papers that helped me implement even more powerful agents that converge faster. Among these advanced techniques were Trust Region Policy Optimization (TRPO), Proximal Policy Optimization (PPO), and Actor-Critic.

I decided to create this website because it all seems to be in the past. I needed a reminder of an exciting learning experience. In a couple of years, when I’m ready to pick RL again, I’d also find a library of resources carefully curated for me.
