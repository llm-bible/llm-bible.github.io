---
layout: publication
title: 'Virgo: A Preliminary Exploration On Reproducing O1-like MLLM'
authors: Yifan Du, Zikang Liu, Yifan Li, Wayne Xin Zhao, Yuqi Huo, Bingning Wang, Weipeng Chen, Zheng Liu, Zhongyuan Wang, Ji-rong Wen
conference: "Arxiv"
year: 2025
bibkey: du2025preliminary
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.01904'}
  - {name: "Code", url: 'https://github.com/RUCAIBox/Virgo'}
tags: ['Attention Mechanism', 'Has Code', 'RAG', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Multimodal Models', 'Pretraining Methods']
---
Recently, slow-thinking reasoning systems, built upon large language models
(LLMs), have garnered widespread attention by scaling the thinking time during
inference. There is also growing interest in adapting this capability to
multimodal large language models (MLLMs). Given that MLLMs handle more complex
data semantics across different modalities, it is intuitively more challenging
to implement multimodal slow-thinking systems.
  To address this issue, in this paper, we explore a straightforward approach
by fine-tuning a capable MLLM with a small amount of textual long-form thought
data, resulting in a multimodal slow-thinking system, Virgo (Visual reasoning
with long thought). We find that these long-form reasoning processes, expressed
in natural language, can be effectively transferred to MLLMs. Moreover, it
seems that such textual reasoning data can be even more effective than visual
reasoning data in eliciting the slow-thinking capacities of MLLMs. While this
work is preliminary, it demonstrates that slow-thinking capacities are
fundamentally associated with the language model component, which can be
transferred across modalities or domains. This finding can be leveraged to
guide the development of more powerful slow-thinking reasoning systems. We
release our resources at https://github.com/RUCAIBox/Virgo.
