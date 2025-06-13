---
layout: publication
title: 'Liger: Linearizing Large Language Models To Gated Recurrent Structures'
authors: Disen Lan, Weigao Sun, Jiaxi Hu, Jusen Du, Yu Cheng
conference: "Arxiv"
year: 2025
bibkey: lan2025linearizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01496"}
  - {name: "Code", url: "https://github.com/OpenSparseLLMs/Linearization"}
tags: ['Fine-Tuning', 'Transformer', 'Pre-Training', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods']
---
Transformers with linear recurrent modeling offer linear-time training and
constant-memory inference. Despite their demonstrated efficiency and
performance, pretraining such non-standard architectures from scratch remains
costly and risky. The linearization of large language models (LLMs) transforms
pretrained standard models into linear recurrent structures, enabling more
efficient deployment. However, current linearization methods typically
introduce additional feature map modules that require extensive fine-tuning and
overlook the gating mechanisms used in state-of-the-art linear recurrent
models. To address these issues, this paper presents Liger, short for
Linearizing LLMs to gated recurrent structures. Liger is a novel approach for
converting pretrained LLMs into gated linear recurrent models without adding
extra parameters. It repurposes the pretrained key matrix weights to construct
diverse gating mechanisms, facilitating the formation of various gated
recurrent structures while avoiding the need to train additional components
from scratch. Using lightweight fine-tuning with Low-Rank Adaptation (LoRA),
Liger restores the performance of the linearized gated recurrent models to
match that of the original LLMs. Additionally, we introduce Liger Attention, an
intra-layer hybrid attention mechanism, which significantly recovers 93% of
the Transformer-based LLM at 0.02% pre-training tokens during the
linearization process, achieving competitive results across multiple
benchmarks, as validated on models ranging from 1B to 8B parameters. Code is
available at https://github.com/OpenSparseLLMs/Linearization.
