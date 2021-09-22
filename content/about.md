---
title: About
---

#### Contents
* [What Is This Website?](#what-is-this-website)
* [What Is RL?](#what-is-rl)
* [Why Is RL Interesting?](#why-is-rl-interesting)
* [How Does RL Work?](#how-does-rl-work)

---

### What Is This Website?

This website compiles a list of research papers and resources to describe the evolution of RL algorithms over time. It’s a resource meant for novice researchers and hobbyists to learn more about breakthroughs in RL throughout the years.

---

### What Is RL?

RL is a machine learning paradigm that seeks to make optimal decisions by studying sequences of correlated events.

---

## Why Is RL Interesting?

In the late 20th century, AI researchers attempted to model different complex problems using  RL frameworks. After decades of research, their efforts were to no avail. Although RL didn’t initially seem to be a promising field of study, true believers never lost hope. 

Ultimately, their persistence paid off. Fueled by new advances in [deep learning](https://en.wikipedia.org/wiki/Deep_learning), RL has finally taken off in the last few years. The paradigm has tackled many challenges that AI researchers had only recently declared to be decades out of reach.

In 2013, computer programs employing RL  were able to outperform humans in Atari games. In 2016, Alpha Go, a computer program, beat 18-time world champion Lee Sedol. Other programs went on to defeat professional players in many other games, including Poker, Dota, and Starcraft.

These achievements didn’t go unnoticed, with RL researchers soon having featured articles in top computer science conferences and the academia’s most prestigious journals, [Nature](https://www.nature.com/) and [Science](https://www.science.org/).

Games have provided the perfect test environment for different RL algorithms, although researchers have since refocused RL on more practical uses. See RL shines in solving complex problems that require planning a few steps ahead like robotics, exploration rovers, and of course, self-driving cars. Moreover, it’s used in bid optimization for online ad auctions and delivering individually tailored recommendations for your next song or movie.

In 2020, RL seemed to be on a trajectory to change the world as we know it. Nowadays, AI researchers believe that RL could one day bring us closer to [Artificial General Intelligence](https://en.wikipedia.org/wiki/Artificial_general_intelligence), i.e., the creation of intelligent agents capable of understanding or learning any intellectual task. In short, these computer programs would be capable of passing the well-known [Turing test](https://en.wikipedia.org/wiki/Turing_test).

---

## How Does RL Work?

Reinforcement Learning is a branch of machine learning that studies optimal decision-making to maximize a reward function (the equivalent of winning a game). Different algorithms attempt to maximize the reward differently, either by maximizing the value function, value-action function, policy, or a combination.

RL can either be model-based, with the algorithm attempting to figure out the transitions of the environment, or model-free, where the algorithm doesn’t care about learning the environment and focuses solely on maximizing a reward function or achieving a near-optimal policy.

Many RL problems are modeled as [Markovian Decision Processes(MDPs)](https://en.wikipedia.org/wiki/Markov_decision_process), which are mostly partially observed. It also leverages [dynamic programming](https://en.wikipedia.org/wiki/Dynamic_programming), [Monte Carlo simulations](https://en.wikipedia.org/wiki/Monte_Carlo_method), and of course, [neural networks](https://en.wikipedia.org/wiki/Artificial_neural_network).

In his seminal [reference](http://incompleteideas.net/book/the-book-2nd.html), [Richard Sutton](https://en.wikipedia.org/wiki/Richard_S._Sutton) writes: “Almost all reinforcement learning algorithms involve estimating value functions.”