---
layout: publication
title: 'Dualad: Dual-layer Planning For Reasoning In Autonomous Driving'
authors: Dingrui Wang, Marc Kaufeld, Johannes Betz
conference: "Arxiv"
year: 2024
bibkey: wang2024dual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.18053'}
tags: ['Tools']
---
We present a novel autonomous driving framework, DualAD, designed to imitate
human reasoning during driving. DualAD comprises two layers: a rule-based
motion planner at the bottom layer that handles routine driving tasks requiring
minimal reasoning, and an upper layer featuring a rule-based text encoder that
converts driving scenarios from absolute states into text description. This
text is then processed by a large language model (LLM) to make driving
decisions. The upper layer intervenes in the bottom layer's decisions when
potential danger is detected, mimicking human reasoning in critical situations.
Closed-loop experiments demonstrate that DualAD, using a zero-shot pre-trained
model, significantly outperforms rule-based motion planners that lack reasoning
abilities. Our experiments also highlight the effectiveness of the text
encoder, which considerably enhances the model's scenario understanding.
Additionally, the integrated DualAD model improves with stronger LLMs,
indicating the framework's potential for further enhancement. Code and
benchmarks are available at github.com/TUM-AVS/DualAD.
