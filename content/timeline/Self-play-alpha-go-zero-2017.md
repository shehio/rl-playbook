---
author:
  name: ""
date: 19 Oct 2017
linktitle:
type:
- post
- posts
title: Mastering the game of Go without human knowledge
eventname:
eventlocation:  
weight: 10
---

## Abstract

<figure>
  <img src="/images/Alpha-Go-Zero.png" />
</figure>

A long-standing goal of artificial intelligence is an algorithm that learns, tabula rasa, superhuman proficiency in challenging domains. Recently, AlphaGo became the first program to defeat a world champion in the game of Go. The tree search in AlphaGo evaluated positions and selected moves using deep neural networks. These neural networks were trained by supervised learning from human expert moves, and by reinforcement learning from self-play. Here we introduce an algorithm based solely on reinforcement learning, without human data, guidance or domain knowledge beyond game rules. AlphaGo becomes its own teacher: a neural network is trained to predict AlphaGo's own move selections and also the winner of AlphaGo's games. This neural network improves the strength of the tree search, resulting in higher quality move selection and stronger self-play in the next iteration. Starting tabula rasa, our new program AlphaGo Zero achieved superhuman performance, winning 100-0 against the previously published, champion-defeating AlphaGo.

[Nature Article](https://www.nature.com/articles/nature24270)

[Paper](https://www.nature.com/articles/nature24270.epdf?sharing_token=Urd8Xo0dBqkq96ZG2bJAiNRgN0jAjWel9jnR3ZoTv0MzTglC12p1NiU2orOu-c1nBdYrrl5mO_G-4ivReqyPdGtpXIYZu2l7Mf8cQvvSKvsnA_tYG0ETemCRq4NAeEGa7s3Q5cxdhxdo4diqVNKfVv6z3pxjfJItf-_W8sMFzoEZgx9ZoMmgzTVWfy37nJ0Zel_NDqMt0C2d3XoGTl7rgX4DHsXdaqmx37M4elyLPpc%3D)
