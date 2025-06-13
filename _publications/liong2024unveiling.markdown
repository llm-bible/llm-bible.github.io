---
layout: publication
title: 'Unveiling Vulnerability Of Self-attention'
authors: Khai Jiet Liong, Hongqiu Wu, Hai Zhao
conference: "Arxiv"
year: 2024
bibkey: liong2024unveiling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.16470'}
tags: ['Attention Mechanism', 'Transformer', 'Security', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Pre-trained language models (PLMs) are shown to be vulnerable to minor word
changes, which poses a big threat to real-world systems. While previous studies
directly focus on manipulating word inputs, they are limited by their means of
generating adversarial samples, lacking generalization to versatile real-world
attack. This paper studies the basic structure of transformer-based PLMs, the
self-attention (SA) mechanism. (1) We propose a powerful perturbation technique
\textit\{HackAttend\}, which perturbs the attention scores within the SA matrices
via meticulously crafted attention masks. We show that state-of-the-art PLMs
fall into heavy vulnerability that minor attention perturbations \\((1%)\\) can
produce a very high attack success rate \\((98%)\\). Our paper expands the
conventional text attack of word perturbations to more general structural
perturbations. (2) We introduce \textit\{S-Attend\}, a novel smoothing technique
that effectively makes SA robust via structural perturbations. We empirically
demonstrate that this simple yet effective technique achieves robust
performance on par with adversarial training when facing various text
attackers. Code is publicly available at \url\{github.com/liongkj/HackAttend\}.
