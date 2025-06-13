---
layout: publication
title: 'RWKV-7 "goose" With Expressive Dynamic State Evolution'
authors: Bo Peng, Ruichong Zhang, Daniel Goldstein, Eric Alcaide, Xingjian Du, Haowen Hou, Jiaju Lin, Jiaxing Liu, Janna Lu, William Merrill, Guangyu Song, Kaifeng Tan, Saiteja Utpala, Nathan Wilce, Johan S. Wind, Tianyi Wu, Daniel Wuttke, Christian Zhou-zheng
conference: "Arxiv"
year: 2025
bibkey: peng2025rwkv
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.14456"}
  - {name: "Code", url: "https://huggingface.co/RWKV,"}
  - {name: "Code", url: "https://github.com/RWKV/RWKV-LM"}
tags: ['Transformer', 'Language Modeling', 'Model Architecture', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
We present RWKV-7 "Goose", a new sequence modeling architecture with constant
memory usage and constant inference time per token. Despite being trained on
dramatically fewer tokens than other top models, our 2.9 billion parameter
language model achieves a new 3B SoTA on multilingual tasks and matches the
current 3B SoTA on English language downstream performance. RWKV-7 introduces a
newly generalized formulation of the delta rule with vector-valued gating and
in-context learning rates, as well as a relaxed value replacement rule. We show
that RWKV-7 can perform state tracking and recognize all regular languages,
while retaining parallelizability of training. This exceeds the capabilities of
Transformers under standard complexity conjectures, which are limited to
\\(\mathsf\{TC\}^0\\). To demonstrate RWKV-7's language modeling capability, we also
present an extended open source 3.1 trillion token multilingual corpus, and
train four RWKV-7 models ranging from 0.19 billion to 2.9 billion parameters on
this dataset.
  To foster openness, reproduction, and adoption, we release our models and
dataset component listing at https://huggingface.co/RWKV, and our training and
inference code at https://github.com/RWKV/RWKV-LM all under the Apache 2.0
License.
