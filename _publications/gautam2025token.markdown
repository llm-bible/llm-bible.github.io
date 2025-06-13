---
layout: publication
title: 'Token-driven Gammatune: Adaptive Calibration For Enhanced Speculative Decoding'
authors: Aayush Gautam, Susav Shrestha, Narasimha Reddy
conference: "Arxiv"
year: 2025
bibkey: gautam2025token
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.00030'}
tags: ['Reinforcement Learning', 'RAG', 'Training Techniques']
---
Speculative decoding accelerates large language model (LLM) inference by using a smaller draft model to propose tokens, which are then verified by a larger target model. However, selecting an optimal speculation length is critical for maximizing speedup while minimizing wasted computation. We introduce \textit\{GammaTune\} and \textit\{GammaTune+\}, training-free adaptive algorithms that dynamically adjust speculation length based on token acceptance rates using a heuristic-based switching mechanism. Evaluated on SpecBench across multiple tasks and model pairs, our method outperforms other heuristic-based approaches and fixed-length speculative decoding, achieving an average speedup of 15% (\\(\pm\\)5%) with \textit\{GammaTune\} and 16% (\\(\pm\\)3%) with \textit\{GammaTune+\}, while reducing performance variance. This makes \textit\{GammaTune\} a robust and efficient solution for real-world deployment.
