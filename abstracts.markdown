---
layout: single
title: Abstracts
permalink: /abstracts/
toc: true
toc_label: "Speaker"
toc_sticky: true
author_profile: false
---


## John Duchi
*On the intersection between privacy, statistical inference, and optimality*

In this talk, I will give an overview and then a deeper dive on estimation under privacy constraints. Beginning from definitional aspects of privacy, I will transition to some of the tools my students, colleagues, and I have developed to provide various guarantees of optimality in estimation problems. These ideas will range from worst-case (minimax) bounds to more recent nuanced bounds that open the doors to instance optimality in private estimation, inspired by classical asymptotic and non-asymptotic notions of optimality. As part of our development, we will exhibit a complementary collection of estimators, including what we term the inverse sensitivity mechanisms, that exhibit various notions of optimality: minimax, instance, or others, for a large class of problems.

## Jevgenijs Ivanovs
*Implementable coupling of a Lévy process and a Brownian motion*

We provide a simple algorithm for construction of Brownian paths approximating those of a Lévy process on a finite time interval. It requires knowledge of the Lévy process trajectory on a chosen regular grid and the law of its endpoint, or the ability to simulate from that. This algorithm is based on reordering of Brownian increments, and it can be applied in a recursive manner. We establish an upper bound on the mean squared maximal distance between the paths and determine a suitable mesh size in various asymptotic regimes. The analysis proceeds by reduction to the comonotonic coupling of increments. Applications to model risk and multilevel Monte Carlo are discussed in detail, and numerical examples are provided.\\
This is a joint work with [Vladimir Fomichov](https://arxiv.org/search/math?searchtype=author&query=Fomichov%2C+V) and [Jorge González Cázares](https://arxiv.org/search/math?searchtype=author&query=C%C3%A1zares%2C+J+G).

## Claudia Klüppelberg
*Conditional independence in max-linear Bayesian networks: impact graphs, source graphs, and &#65121;-dependence*

Motivated by extreme risk analysis, max-linear graphical models have been introduced and studied with the goal to follow extreme events spreading through a network. This is quite different to to classical graphical models, where the focus is on dependence around the mean of data. We present max-linear models naturally in the framework of tropical geometry. This perspective allows us to shed light on some known results and to prove others with algebraic techniques. In particular, we give a complete description of conditional independence relations for max-linear Bayesian networks.\\
This is joint work with Carlos Améndola, Steffen Lauritzen, and Ngoc Tran, based on the paper
*Améndola, C., Klüppelberg, C., Lauritzen, S., and Tran, N. (2021)
Conditional Independence in Max-linear Bayesian Networks.
Ann. Appl. Prob. forthcoming.*

## Laurent Massoulié
*Partial alignment of sparse random graphs*

## Gareth Roberts
*Limits of simulated and parallel tempering schemes in high dimensions*

Simulated tempering (ST) and parallel tempering (PT) have proved to be a highly effective MCMC algorithm for sampling from multi-modal distributions. It works on the principle that for any given target density $\pi (x)$, simulation from a density proportional to $\pi(x)^{1/T}$  for $T>1$ is usually much easier than sampling directly from $\pi(x)$. Basic simulated tempering therefore constructs a Markov chain $(x, T)$ consisting of within-temperature moves which adjust $x$, and between-temperature moves which change $T$ within a discrete grid of possible $T$ values. Parallel tempering works similarly but maintains an ensemble of particles, one at each temperature, with particles at neighbouring temperatures occasionally swapping. Lack of analytic tractability of these Markov chains means that study of their mixing properties are complicated. However it is possible to analyse stylised versions of multi-modal problems in the high-dimensional limit.\\
This talk will consider such limits in different contexts. These limits are normally expressed as diffusions (or skew-diffusions) on (some version of) the temperature space. One practical consideration for implementing these algorithms  concerns the choice of temperature grid. Our analysis allows practical guidance  on this choice. The analysis also sheds light on limitations to the properties of ST and PT and suggests methodological improvements which can be similarly analysed. In particular the Annealed Leap-Point Sampler (ALPS) which, somewhat counter-intuitively also utilises temperatures $T\ll 1$ in order to obtain good mixing properties.\\
This work is mainly joint work with Nick Tawn and/or Jeff Rosenthal.


## Devavrat Shah
*Towards causal reinforcement learning*

## Ben Van Roy
*Reinforcement learning, bit by bit*

## Garrett Van Ryzin
*Labor cost free-riding in the gig economy*

We propose a theory of gig economies in which workers participate in a shared labor pool utilized by multiple firms. Since firms share the same pool of workers, they face a trade-off in setting pay rates; high pay rates are necessary to maintain a large worker pool and thus reduce the likelihood of lost demand, but they also lower a firm’s profit margin. We prove that larger firms pay more than smaller firms in the resulting pay equilibrium. These diseconomies of scale are strong too; firms smaller than a critical size pay the minimal rate possible (the workers’ reservation wage), while all firms larger than the critical size earn the same total profit regardless of size. This scale disadvantage in labor costs contradicts the conventional wisdom that gig companies enjoy strong network effects and suggests that small firms have significant incentives to join an existing gig economy, implying gig markets are highly contestable. Yet we also show that the formation of a gig economy requires the existence of a large firm, in the sense that an equilibrium without any firms participating only exists when no single firm has enough demand to form a gig economy on its own. The findings are consistent with stylized facts about the evolution of gig markets such as ridesharing.\\
This is [joint work](https://ssrn.com/abstract=3775888) with Zhen Lian and Sebastien Martin.

## Mengdi Wang
*Compressive state representation learning from dynamic data towards small-data RL applications*
