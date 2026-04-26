---
layout: single
title: Abstracts
permalink: /abstracts/
toc: true
toc_label: "Speaker"
toc_sticky: true
author_profile: false
---

## Søren Asmussen
*On Wiener-Hopf factorization and Erlangization, with applications to finance and queueing*

The Wiener-Hopf factorization of a Lévy process $X$ at an independent exponential time $e_1$ states that the maximum $\overline X(e_1)$ and terminal value $X(e_1)$ are independent. We present an extension to regime-switching models up to a more general time horizon. This covers in particular Canadization/Erlangization, meaning that a fixed horizon $T$ is approximated by an Erlang r.v. (a sum of $q$ i.i.d. exponentials) with mean $T$. Under the traditional assumption that jumps are phase-type, we present an iterative matrix algorithm for the marginal distributions of the Wiener-Hopf factors. From this together with the factorisation, option prices and transient queueing solutions come out as limits as $q\to\infty$ of closed matrix expressions. Here Richardson extrapolation allows to keep $q$ and hence matrix dimensions quite small. The approach avoids otherwise dominant features in the literature such as numerical transform inversion and expansions in terms of roots determined by analytic continuation and Rouch\’e’s theorem . The class of models is dense in the whole space of cadlag processes. A number of examples are presented.

## Ton Dieker
*QPLEX Decision Processes*

We introduce a QPLEX Decision Process (QDP) as a model for dynamic control of queueing systems with non-stationary arrivals, general service distributions, and service-level chance constraints. QDPs integrate QPLEX, a computational modeling methodology for transient analysis of stochastic systems, into a nonlinear Markov decision framework. Since QPLEX approximations use nonlinear transition probabilities with orders-of-magnitude smaller state spaces, QDPs circumvent the curse of dimensionality associated with general service times. Via forward and backward iterative schemes, we can rapidly compute gradients deterministically on the much smaller state space, eliminating sampling variance. We further address optimization through natural-gradient-inspired methods with block-diagonal Fisher approximations. To illustrate the QDP methodology, we formulate a single-station dynamic pricing problem with non-stationary demand as a QDP. When the reward structure uses waiting and terminal costs, our approach can find near-optimal policies in seconds on a single CPU; when the reward structure uses penalties for deviating from service-level chance constraints, the optimization landscape is substantially more challenging yet our approach can find a high-quality, practical policy in approximately a minute on a single CPU. 

## Jing Dong
*Service-Induced Congestion in Memory-Constrained LLM Serving*

In large language model (LLM) serving, each request accumulates persistent memory during service as its key–value cache grows with every generated token. Under high concurrency, aggregate memory usage therefore increases endogenously over time: the service process itself creates future capacity pressure. When memory capacity is exceeded, systems must evict active requests, i.e., discarding their cached state and restarting them later, which wastes computation and reduces throughput. This progressive resource consumption breaks the monotonicity assumptions underlying classical queueing stability analyses and gives rise to a new form of service-induced congestion. In this work, we develop a discrete-time dynamical model of memory-constrained LLM inference that captures the interaction among admission, memory growth, and throughput under continuous batching. In the saturated-input regime, the system admits both eviction-free fixed points and periodic limit cycles with evictions. For homogeneous workloads, we show that the eviction-free equilibrium is unstable under standard batching dynamics and that the system converges to a unique asymptotically stable worst-case limit cycle, where throughput losses can reach 50%. For heterogeneous workloads, we establish a sharp stability dichotomy. Under a large-prompt scaling regime, the eviction-free equilibrium is asymptotically stable if and only if the decoding lengths are coprime. This result characterizes when workload heterogeneity desynchronizes completion events and stabilizes the system. More broadly, we identify service-induced congestion as a structural instability mechanism in memory-constrained systems and determine when heterogeneity restores stability.

## Paul Glasserman
*Importance Sampling for Latent Dirichlet Allocation*

-

## Peter Glynn
*Forty Years of Regeneration*

Among Karl Sigman’s major contributions to applied probability are those connected to regeneration and its application to queues. Regeneration is a powerful tool in the analysis of Markov chains and processes in particular. In this talk, we will describe some of Karl’s work in this area, and discuss how the area has evolved in the years since Karl entered the field. In particular, we will touch on various characterizations of Harris recurrence, the use of regeneration in establishing necessary and sufficient conditions for the validity of various limit theorems, and the use of regeneration algorithmically, especially in the simulation of Markov chains and processes.

## Henry Lam
*Start Safe: Configuring Optimization Algorithms for Decision-Making under Extreme Risks*

We consider stochastic optimization where the goal is not only to optimize an average-case objective, but also mitigate the occurrence and impact of extreme catastrophic events. When a simulation model is present, variance reduction techniques are naturally employed to control estimation errors due to event rarity. We argue, however, that natural attempts to integrate variance reduction into optimization, even executed in a reasonable adaptive fashion, encounters fundamental challenges in terms of guaranteeing realistic runtime when using common stochastic gradient descent algorithms. On a high level, the challenge arises from the extreme sensitivity of tail-based objectives with respect to the decision variables, which renders the failure of traditional Lipschitz-based analyses. We offer remedies based on a notion of "safe initialization", combined with careful update iterations, that allow for finite-time error control. We discuss implications of our findings on safe decision search and extremal predictive modeling.

## Alan Scheller-Wolf
*SPLIT: SymPathy for Large Jobs Improves Tail Latency*

-

## Wenpin Tang 
*Stochastic approaches to conditional diffusion guidance and applications*

Recently, there has been growing interest in guiding, or fine tuning pretrained diffusion models for specific purposes, e.g., aesthetic quality of images, functional property of proteins, and downstream tasks in finance and operations management. In this talk, I will present a novel approach to conditional diffusion guidance in the context of classifier guidance. The approach is probability-theoretic, relying on various techniques such as martingale, quadratic variations, etc. I will also discuss some applications including the generation of synthetic queueing and financial data.

## Assaf Zeevi
*Sampling with Sigman*

Among Karl’s many contributions in applied probability, a somewhat lesser known piece of work (w/ Peter Glynn) studies a very basic question: does the PASTA principle (Poisson Arrivals See Time Averages) hold for more general classes of renewal process sampling mechanisms. Namely, if we sample a continuous time stochastic process according to the event times of a renewal process, does the average of the sampled process converge to the long run average computed by observing the entire path of that process (assuming it admits such a limit). This is among my favorite papers, and in the talk I’ll try to explain why…

<!--
## John Duchi
*On the intersection between privacy, statistical inference, and optimality*

In this talk, I will give an overview and then a deeper dive on estimation under privacy constraints. Beginning from definitional aspects of privacy, I will transition to some of the tools my students, colleagues, and I have developed to provide various guarantees of optimality in estimation problems. These ideas will range from worst-case (minimax) bounds to more recent nuanced bounds that open the doors to instance optimality in private estimation, inspired by classical asymptotic and non-asymptotic notions of optimality. As part of our development, we will exhibit a complementary collection of estimators, including what we term the inverse sensitivity mechanisms, that exhibit various notions of optimality: minimax, instance, or others, for a large class of problems.

## Jevgenijs Ivanovs
*Implementable coupling of a Lévy process and a Brownian motion*

We provide a simple algorithm for construction of Brownian paths approximating those of a Lévy process on a finite time interval. It requires knowledge of the Lévy process trajectory on a chosen regular grid and the law of its endpoint, or the ability to simulate from that. This algorithm is based on reordering of Brownian increments, and it can be applied in a recursive manner. We establish an upper bound on the mean squared maximal distance between the paths and determine a suitable mesh size in various asymptotic regimes. The analysis proceeds by reduction to the comonotonic coupling of increments. Applications to model risk and multilevel Monte Carlo are discussed in detail, and numerical examples are provided.\\
This is a joint work with [Vladimir Fomichov](https://arxiv.org/search/math?searchtype=author&query=Fomichov%2C+V) and [Jorge González Cázares](https://arxiv.org/search/math?searchtype=author&query=C%C3%A1zares%2C+J+G).\\
Slides are [here](slides/ivanovs.pdf).

## Claudia Klüppelberg
*Conditional independence in max-linear Bayesian networks: impact graphs, source graphs, and &#65121;-dependence*

Motivated by extreme risk analysis, max-linear graphical models have been introduced and studied with the goal to follow extreme events spreading through a network. This is quite different to to classical graphical models, where the focus is on dependence around the mean of data. We present max-linear models naturally in the framework of tropical geometry. This perspective allows us to shed light on some known results and to prove others with algebraic techniques. In particular, we give a complete description of conditional independence relations for max-linear Bayesian networks.\\
This is joint work with Carlos Améndola, Steffen Lauritzen, and Ngoc Tran, based on the paper
*Améndola, C., Klüppelberg, C., Lauritzen, S., and Tran, N. (2021)
Conditional Independence in Max-linear Bayesian Networks.
Ann. Appl. Prob. forthcoming.*\\
Slides are [here](slides/kluppelberg.pdf).

## Laurent Massoulié
*Partial alignment of sparse random graphs*

Graph alignment is a generic algorithmic problem with many applications. In this work we consider alignment of sparse random graphs generated from the correlated Erdös-Rényi distribution. We introduce the Neighborhood Tree Matching Algorithm which provably returns -- in polynomial time -- a positive fraction of correctly matched vertices, and a vanishing fraction of mismatches. This result holds in a challenging regime of graphs with average degree in $O(1)$ and correlation parameter bounded away from 1. As a byproduct of the analysis we introduce a matching metric between trees and characterize it for several models of correlated random trees. If time allows we shall also describe recent results giving information-theoretic upper bounds on the best possible partial alignment achievable by any algorithm, polynomial-time or not, and improved conditions for partial alignment in poly-time. \\
This is based on joint works with [Luca Ganassali](https://arxiv.org/abs/2002.01258) and [Marc Lelarge](https://arxiv.org/pdf/2102.02685.pdf).

## Gareth Roberts
*Limits of simulated and parallel tempering schemes in high dimensions*

Simulated tempering (ST) and parallel tempering (PT) have proved to be a highly effective MCMC algorithm for sampling from multi-modal distributions. It works on the principle that for any given target density $\pi (x)$, simulation from a density proportional to $\pi(x)^{1/T}$  for $T>1$ is usually much easier than sampling directly from $\pi(x)$. Basic simulated tempering therefore constructs a Markov chain $(x, T)$ consisting of within-temperature moves which adjust $x$, and between-temperature moves which change $T$ within a discrete grid of possible $T$ values. Parallel tempering works similarly but maintains an ensemble of particles, one at each temperature, with particles at neighbouring temperatures occasionally swapping. Lack of analytic tractability of these Markov chains means that study of their mixing properties are complicated. However it is possible to analyse stylised versions of multi-modal problems in the high-dimensional limit.\\
This talk will consider such limits in different contexts. These limits are normally expressed as diffusions (or skew-diffusions) on (some version of) the temperature space. One practical consideration for implementing these algorithms  concerns the choice of temperature grid. Our analysis allows practical guidance  on this choice. The analysis also sheds light on limitations to the properties of ST and PT and suggests methodological improvements which can be similarly analysed. In particular the Annealed Leap-Point Sampler (ALPS) which, somewhat counter-intuitively also utilises temperatures $T\ll 1$ in order to obtain good mixing properties.\\
This work is mainly joint work with Nick Tawn and/or Jeff Rosenthal.\\
Slides are [here](slides/roberts.pdf).

## Devavrat Shah
*Causal tensor estimation*

In this talk, we present a framework for causal inference for the “panel” or “longitudinal” setting from the lens of tensor estimation. Traditionally, such panel or longitudinal settings are considered in Econometrics literature for program or policy evaluation. Tensor estimation has been considered in Machine learning where tantalizing statistical and computational tradeoffs have emerged for random observation models. We introduce a causal variant of tensor estimation that provides a unified view for prior works in Econometrics as well as provides newer avenues to explore. We discuss a method for estimating such a causal variant of the tensor. We discuss various exciting directions for future research including offline reinforcement learning. \\
This is based on joint work with Alberto Abadie (MIT), Anish Agarwal (MIT) and Dennis Shen (MIT/UC Berkeley).\\
Slides are [here](slides/shah.pdf).

## Ben Van Roy
*Simple agent, complex environment: efficient reinforcement learning with agent states*

I will present a simple reinforcement learning agent that implements an optimistic version of Q-learning and results establishing that this agent can operate with some level of competence in any environment.  The results apply even when the environment is arbitrarily complex — and much more so than the agent — and treat a general agent-environment interface, involving a single stream of experience.  This level of generality positions the results to inform the design of future agents for operation in complex real environments.  I will also discuss some open issues related to the agent and analysis.\\
The paper is [here](slides/vanroy.pdf).

## Garrett van Ryzin
*Labor cost free-riding in the gig economy*

We propose a theory of gig economies in which workers participate in a shared labor pool utilized by multiple firms. Since firms share the same pool of workers, they face a trade-off in setting pay rates; high pay rates are necessary to maintain a large worker pool and thus reduce the likelihood of lost demand, but they also lower a firm’s profit margin. We prove that larger firms pay more than smaller firms in the resulting pay equilibrium. These diseconomies of scale are strong too; firms smaller than a critical size pay the minimal rate possible (the workers’ reservation wage), while all firms larger than the critical size earn the same total profit regardless of size. This scale disadvantage in labor costs contradicts the conventional wisdom that gig companies enjoy strong network effects and suggests that small firms have significant incentives to join an existing gig economy, implying gig markets are highly contestable. Yet we also show that the formation of a gig economy requires the existence of a large firm, in the sense that an equilibrium without any firms participating only exists when no single firm has enough demand to form a gig economy on its own. The findings are consistent with stylized facts about the evolution of gig markets such as ridesharing.\\
This is [joint work](https://ssrn.com/abstract=3775888) with Zhen Lian and Sebastien Martin.

## Mengdi Wang
*Compressive state representation learning towards small-data RL applications*

In this talk we survey recent advances on statistical efficiency and regret of reinforcement learning (RL) when good state representations are available. Motivated by the RL theory, we discuss what should be good state representations for RL and how to  find compact state embeddings from high-dimensional Markov state trajectories. In the spirit of diffusion map for dynamical systems, we propose an efficient method for learning a low-dimensional state embedding and capturing the process's dynamics. State embedding can be used to cluster states into metastable sets predict future dynamics, and enable generalizable downstream machine learning and reinforcement learning tasks. We demonstrated applications of the approach in games, clinical pathway optimization, single-cell biology and identification of gene markers for drug discovery.
-->