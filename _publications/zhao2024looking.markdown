---
layout: publication
title: 'Looking Beyond Text: Reducing Language Bias In Large Vision-language Models Via Multimodal Dual-attention And Soft-image Guidance'
authors: Haozhe Zhao, Shuzheng Si, Liang Chen, Yichi Zhang, Maosong Sun, Mingjia Zhang, Baobao Chang
conference: "Arxiv"
year: 2024
bibkey: zhao2024looking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.14279'}
  - {name: "Code", url: 'https://lacing-lvlm.github.io)'}
tags: ['Attention Mechanism', 'Has Code', 'Transformer', 'Training Techniques', 'Model Architecture', 'Tools', 'Prompting', 'Multimodal Models', 'Ethics and Bias', 'Pretraining Methods']
---
Large vision-language models (LVLMs) have achieved impressive results in
various vision-language tasks. However, despite showing promising performance,
LVLMs suffer from hallucinations caused by language bias, leading to diminished
focus on images and ineffective visual comprehension. We identify two primary
reasons for this bias: 1. Different scales of training data between the
pretraining stage of LLM and multimodal alignment stage. 2. The learned
inference bias due to short-term dependency of text data. Therefore, we propose
LACING, a systemic framework designed to address the language bias of LVLMs
with muLtimodal duAl-attention meChanIsm (MDA) aNd soft-image Guidance (IFG).
Specifically, MDA introduces a parallel dual-attention mechanism that enhances
the integration of visual inputs across the model. IFG introduces a learnable
soft visual prompt during training and inference to replace visual inputs,
designed to compel LVLMs to prioritize text inputs. Then, IFG further proposes
a novel decoding strategy using the soft visual prompt to mitigate the model's
over-reliance on adjacent text inputs. Comprehensive experiments demonstrate
that our method effectively debiases LVLMs from their language bias, enhancing
visual comprehension and reducing hallucinations without requiring additional
training resources or data. The code and model are available at
[lacing-lvlm.github.io](https://lacing-lvlm.github.io).
