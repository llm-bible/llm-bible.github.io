---
layout: publication
title: 'Hallucana: Fixing LLM Hallucination With A Canary Lookahead'
authors: Tianyi Li, Erenay Dayanik, Shubhi Tyagi, Andrea Pierleoni
conference: "Arxiv"
year: 2024
bibkey: li2024fixing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.07965'}
tags: ['Reinforcement Learning', 'Pre-Training', 'Training Techniques']
---
In this paper, we present HalluCana, a canary lookahead to detect and correct
factuality hallucinations of Large Language Models (LLMs) in long-form
generation. HalluCana detects and intervenes as soon as traces of hallucination
emerge, during and even before generation. To support timely detection, we
exploit the internal factuality representation in the LLM hidden space, where
we investigate various proxies to the LLMs' factuality self-assessment, and
discuss its relation to the models' context familiarity from their
pre-training. On biography generation, our method improves generation quality
by up to 2.5x, while consuming over 6 times less compute.
