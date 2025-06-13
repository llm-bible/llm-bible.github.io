---
layout: publication
title: 'Flux Already Knows -- Activating Subject-driven Image Generation Without Training'
authors: Hao Kang, Stathi Fotiadis, Liming Jiang, Qing Yan, Yumin Jia, Zichuan Liu, Min Jin Chong, Xin Lu
conference: "Arxiv"
year: 2025
bibkey: kang2025flux
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.11478"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications', 'Attention Mechanism']
---
We propose a simple yet effective zero-shot framework for subject-driven
image generation using a vanilla Flux model. By framing the task as grid-based
image completion and simply replicating the subject image(s) in a mosaic
layout, we activate strong identity-preserving capabilities without any
additional data, training, or inference-time fine-tuning. This "free lunch"
approach is further strengthened by a novel cascade attention design and meta
prompting technique, boosting fidelity and versatility. Experimental results
show that our method outperforms baselines across multiple key metrics in
benchmarks and human preference studies, with trade-offs in certain aspects.
Additionally, it supports diverse edits, including logo insertion, virtual
try-on, and subject replacement or insertion. These results demonstrate that a
pre-trained foundational text-to-image model can enable high-quality,
resource-efficient subject-driven generation, opening new possibilities for
lightweight customization in downstream applications.
