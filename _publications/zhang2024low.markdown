---
layout: publication
title: 'Lolcats: On Low-rank Linearizing Of Large Language Models'
authors: Michael Zhang, Simran Arora, Rahul Chalamala, Alan Wu, Benjamin Spector, Aaryan Singhal, Krithik Ramesh, Christopher Ré
conference: "Arxiv"
year: 2024
bibkey: zhang2024low
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10254"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Fine-Tuning', 'Attention Mechanism']
---
Recent works show we can linearize large language models (LLMs) -- swapping
the quadratic attentions of popular Transformer-based LLMs with subquadratic
analogs, such as linear attention -- avoiding the expensive pretraining costs.
However, linearizing LLMs often significantly degrades model quality, still
requires training over billions of tokens, and remains limited to smaller 1.3B
to 7B LLMs. We thus propose Low-rank Linear Conversion via Attention Transfer
(LoLCATs), a simple two-step method that improves LLM linearizing quality with
orders of magnitudes less memory and compute. We base these steps on two
findings. First, we can replace an LLM's softmax attentions with
closely-approximating linear attentions, simply by training the linear
attentions to match their softmax counterparts with an output MSE loss
("attention transfer"). Then, this enables adjusting for approximation errors
and recovering LLM quality simply with low-rank adaptation (LoRA). LoLCATs
significantly improves linearizing quality, training efficiency, and
scalability. We significantly reduce the linearizing quality gap and produce
state-of-the-art subquadratic LLMs from Llama 3 8B and Mistral 7B v0.1, leading
to 20+ points of improvement on 5-shot MMLU. Furthermore, LoLCATs does so with
only 0.2% of past methods' model parameters and 0.4% of their training tokens.
Finally, we apply LoLCATs to create the first linearized 70B and 405B LLMs (50x
larger than prior work). When compared with prior approaches under the same
compute budgets, LoLCATs significantly improves linearizing quality, closing
the gap between linearized and original Llama 3.1 70B and 405B LLMs by 77.8%
and 78.1% on 5-shot MMLU.
