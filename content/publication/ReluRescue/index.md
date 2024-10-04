---
title: "ReLU to the Rescue: Improve Your On-Policy Actor-Critic with Positive Advantages"
authors:
- Andrew Jesson
- Chris Lu
- admin
- Angelos Filos
- Jakob Nicolaus Foerster
- Yarin Gal


date: "2024-06-01T00:00:00Z"
publishDate: "2024-06-01T00:00:00Z"

# doi: ""

# # Schedule page publish date (NOT publication's date).
# publishDate: "2020-10-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]


# Publication name and optional abbreviated publication name.
publication:  Accepted *ICML 2024* 
publication_short: Accepted *ICML 2024*

abstract: This paper introduces a novel method for enhancing the effectiveness of the Asynchronous Advantage Actor-Critic (A3C) algorithm by incorporating state-aware exploration. We achieve this improvement through three simple yet impactful modifications (1) applying a ReLU function to advantage estimates, (2) using spectral normalization, and (3) incorporating dropout. We prove, under standard assumptions, that restricting policy updates to positive advantages optimizes a lower bound on the value function plus a constant. Further, we show that the constant is bounded proportional to the Lipschitz constant of the value function, which offers theoretical grounding for the use of spectral normalization. r application of dropout corresponds to approximate Bayesian inference over both the actor and critic parameters, which enables prudent exploration around the modes of the actor via Thompson sampling. Extensive empirical evaluations on diverse benchmarks reveal the superior performance of our approach compared to existing on-policy algorithms. Notably, we achieve significant improvements over Proximal Policy Optimization (PPO) in both the challenging ProcGen generalization benchmark, and the MuJoCo benchmark for continuous control.

tags:
- RL

---
