---
layout: publication
title: 'Parameter-efficient Finetuning Of Transformers For Source Code'
authors: Ayupov Shamil, Chirkova Nadezhda
conference: "Arxiv"
year: 2022
bibkey: ayupov2022parameter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.05901"}
tags: ['Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Pretrained Transformers achieve state-of-the-art performance in various
code-processing tasks but may be too large to be deployed. As software
development tools often incorporate modules for various purposes which may
potentially use a single instance of the pretrained model, it appears relevant
to utilize parameter-efficient fine-tuning for the pretrained models of code.
In this work, we test two widely used approaches, adapters and LoRA, which were
initially tested on NLP tasks, on four code-processing tasks. We find that
though the efficient fine-tuning approaches may achieve comparable or higher
performance than the standard, full, fine-tuning in code understanding tasks,
they underperform full fine-tuning in code-generative tasks. These results
underline the importance of testing efficient fine-tuning approaches on other
domains than NLP and motivate future research in efficient fine-tuning for
source code.
