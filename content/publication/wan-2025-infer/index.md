---
title: Infer Human's Intentions Before Following Natural Language Instructions
authors:
- admin
- Yue Wu
- Yiping Wang
- Jiayuan Mao
- Natasha Jaques
author_notes:
  - 
  - 
  - 
  - 'Equal contribution'
  - 'Equal contribution'
date: '2025-01-01'
publishDate: '2024-12-10T23:58:42.829370Z'
publication_types:
- paper-conference
publication: '*AAAI*'
abstract: For AI agents to be helpful to humans, they should be able to follow natural
  language instructions to complete everyday cooperative tasks in human environments.
  However, real human instructions inherently possess ambiguity, because the human
  speakers assume sufficient prior knowledge about their hidden goals and intentions.
  Standard language grounding and planning methods fail to address such ambiguities
  because they do not model human internal goals as additional partially observable
  factors in the environment. We propose a new framework, Follow Instructions with
  Social and Embodied Reasoning (FISER), aiming for better natural language instruction
  following in collaborative embodied tasks. Our framework makes explicit inferences
  about human goals and intentions as intermediate reasoning steps. We implement a
  set of Transformer-based models and evaluate them over a challenging benchmark,
  HandMeThat. We empirically demonstrate that using social reasoning to explicitly
  infer human intentions before making action plans surpasses purely end-to-end approaches.
  We also compare our implementation with strong baselines, including Chain of Thought
  prompting on the largest available pre-trained language models, and find that FISER
  provides better performance on the embodied social reasoning tasks under investigation,
  reaching the state-of-the-art on HandMeThat.
links:
- name: URL
  url: http://arxiv.org/abs/2409.18073
---