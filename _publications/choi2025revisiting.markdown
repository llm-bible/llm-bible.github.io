---
layout: publication
title: 'Revisiting Funnel Transformers For Modern LLM Architectures With Comprehensive Ablations In Training And Inference Configurations'
authors: Donghyun Choi, Lucas Spangher, Chris Hidey, Peter Grabowski, Ramy Eskander
conference: "Arxiv"
year: 2025
bibkey: choi2025revisiting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.02877'}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Applications', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Transformer-based Large Language Models, which suffer from high computational
costs, advance so quickly that techniques proposed to streamline earlier
iterations are not guaranteed to benefit more modern models. Building upon the
Funnel Transformer proposed by Dai and Le (2020), which progressively
compresses intermediate representations, we investigate the impact of funneling
in contemporary Gemma2 Transformer architectures. We systematically evaluate
various funnel configurations and recovery methods, comparing: (1) standard
pretraining to funnel-aware pretraining strategies, (2) the impact of
funnel-aware fine-tuning, and (3) the type of sequence recovery operation. Our
results demonstrate that funneling creates information bottlenecks that
propagate through deeper network layers, particularly in larger models (e.g.,
Gemma 7B), leading to at times unmanageable performance lost. However,
carefully selecting the funneling layer and employing effective recovery
strategies, can substantially mitigate performance losses, achieving up to a
44% reduction in latency. Our findings highlight key trade-offs between
computational efficiency and model accuracy, providing practical guidance for
deploying funnel-based approaches in large-scale natural language applications.
