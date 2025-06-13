---
layout: publication
title: 'Video Diffusion Transformers Are In-context Learners'
authors: Zhengcong Fei, Di Qiu, Debang Li, Changqian Yu, Mingyuan Fan
conference: "Arxiv"
year: 2024
bibkey: fei2024video
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.10783"}
  - {name: "Code", url: "https://github.com/feizc/Video-In-Context"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Language Modeling', 'RAG', 'Merging', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Has Code', 'Prompting', 'Applications']
---
This paper investigates a solution for enabling in-context capabilities of
video diffusion transformers, with minimal tuning required for activation.
Specifically, we propose a simple pipeline to leverage in-context generation:
(\\(\textbf\{i\}\\)) concatenate videos along spacial or time dimension,
(\\(\textbf\{ii\}\\)) jointly caption multi-scene video clips from one source, and
(\\(\textbf\{iii\}\\)) apply task-specific fine-tuning using carefully curated small
datasets. Through a series of diverse controllable tasks, we demonstrate
qualitatively that existing advanced text-to-video models can effectively
perform in-context generation. Notably, it allows for the creation of
consistent multi-scene videos exceeding 30 seconds in duration, without
additional computational overhead. Importantly, this method requires no
modifications to the original models, results in high-fidelity video outputs
that better align with prompt specifications and maintain role consistency. Our
framework presents a valuable tool for the research community and offers
critical insights for advancing product-level controllable video generation
systems. The data, code, and model weights are publicly available at:
https://github.com/feizc/Video-In-Context.
