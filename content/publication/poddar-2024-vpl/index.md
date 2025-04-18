---
title: Personalizing Reinforcement Learning from Human Feedback with Variational Preference
  Learning
authors:
- Sriyash Poddar
- admin
- Hamish Ivison
- Abhishek Gupta
- Natasha Jaques
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 
  - 'Equal contribution'
  - 'Equal contribution'
date: '2024-01-01'
publishDate: '2024-10-27T23:24:51.988055Z'
publication_types:
- paper-conference
publication: '*NeurIPS*'
abstract: Reinforcement Learning from Human Feedback (RLHF) is a powerful paradigm
  for aligning foundation models to human values and preferences. However, current
  RLHF techniques cannot account for the naturally occurring differences in individual
  human preferences across a diverse population. When these differences arise, traditional
  RLHF frameworks simply average over them, leading to inaccurate rewards and poor
  performance for individual subgroups. To address the need for pluralistic alignment,
  we develop a class of multimodal RLHF methods. Our proposed techniques are based
  on a latent variable formulation - inferring a novel user-specific latent and learning
  reward models and policies conditioned on this latent without additional user-specific
  data. While conceptually simple, we show that in practice, this reward modeling
  requires careful algorithmic considerations around model architecture and reward
  scaling. To empirically validate our proposed technique, we first show that it can
  provide a way to combat underspecification in simulated control problems, inferring
  and optimizing user-specific reward functions. Next, we conduct experiments on pluralistic
  language datasets representing diverse user preferences and demonstrate improved
  reward function accuracy. We additionally show the benefits of this probabilistic
  framework in terms of measuring uncertainty, and actively learning user preferences.
  This work enables learning from diverse populations of users with divergent preferences,
  an important challenge that naturally occurs in problems from robot learning to
  foundation model alignment.
links:
- name: URL
  url: http://arxiv.org/abs/2408.10075
---
