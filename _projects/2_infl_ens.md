---
layout: page
title: InflEns
description: A Python research package that implements the influencer's game and routes queries across small language models using proportional allocation and trait-space geometry from Lovett & Fu.
img: assets/img/InflEns.png
importance: 2
category: work
---

**InflEns** (`infl_ens`) extends the influencer's game to routing and learning for small language models.

The package builds a trait space from a calibration corpus, places model agents in that space, and allocates queries with the proportional rule \(G_i(\mathbf{x}, b)\) using a multivariate Gaussian influence kernel. It supports both fixed-position routing and closed-loop training where agents update positions from the traffic they receive.

### Highlights

- The training mechanism inherits the game-theoretic properties of the influencer's game.
- Router agents with proportional allocation and stability thresholds lead to increased interpretability of agent learning and specialization.
- Trait-space construction creates resource landscapes that agents can specialize over.
