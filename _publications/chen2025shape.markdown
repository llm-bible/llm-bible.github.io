---
layout: publication
title: 'SHAPE : Self-improved Visual Preference Alignment By Iteratively Generating Holistic Winner'
authors: Kejia Chen, Jiawen Zhang, Jiacong Hu, Jiazhen Yang, Jian Lou, Zunlei Feng, Mingli Song
conference: "Arxiv"
year: 2025
bibkey: chen2025shape
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.04858"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Tools', 'Pretraining Methods', 'Fine-Tuning', 'Attention Mechanism']
---
Large Visual Language Models (LVLMs) increasingly rely on preference
alignment to ensure reliability, which steers the model behavior via preference
fine-tuning on preference data structured as ``image - winner text - loser
text'' triplets. However, existing approaches often suffer from limited
diversity and high costs associated with human-annotated preference data,
hindering LVLMs from fully achieving their intended alignment capabilities. We
present \projectname, a self-supervised framework capable of transforming the
already abundant supervised text-image pairs into holistic preference triplets
for more effective and cheaper LVLM alignment, eliminating the need for human
preference annotations. Our approach facilitates LVLMs in progressively
enhancing alignment capabilities through iterative self-improvement. The key
design rationale is to devise preference triplets where the winner text
consistently improves in holisticness and outperforms the loser response in
quality, thereby pushing the model to ``strive to the utmost'' of alignment
performance through preference fine-tuning. For each given text-image pair,
SHAPE introduces multiple visual augmentations and pairs them with a summarized
text to serve as the winner response, while designating the original text as
the loser response. Experiments across \textbf\{12\} benchmarks on various model
architectures and sizes, including LLaVA and DeepSeek-VL, show that SHAPE
achieves significant gains, for example, achieving +11.3% on MMVet
(comprehensive evaluation), +1.4% on MMBench (general VQA), and +8.0% on POPE
(hallucination robustness) over baselines in 7B models. Notably, qualitative
analyses confirm enhanced attention to visual details and better alignment with
human preferences for holistic descriptions.
