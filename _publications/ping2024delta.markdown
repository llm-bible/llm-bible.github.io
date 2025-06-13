---
layout: publication
title: 'Delta-come: Training-free Delta-compression With Mixed-precision For Large Language Models'
authors: Bowen Ping, Shuo Wang, Hanqing Wang, Xu Han, Yuzhuang Xu, Yukun Yan, Yun Chen, Baobao Chang, Zhiyuan Liu, Maosong Sun
conference: "Arxiv"
year: 2024
bibkey: ping2024delta
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.08903'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Applications', 'Quantization', 'Fine-Tuning', 'Pretraining Methods']
---
Fine-tuning is a crucial process for adapting large language models (LLMs) to
diverse applications. In certain scenarios, such as multi-tenant serving,
deploying multiple LLMs becomes necessary to meet complex demands. Recent
studies suggest decomposing a fine-tuned LLM into a base model and
corresponding delta weights, which are then compressed using low-rank or
low-bit approaches to reduce costs. In this work, we observe that existing
low-rank and low-bit compression methods can significantly harm the model
performance for task-specific fine-tuned LLMs (e.g., WizardMath for math
problems). Motivated by the long-tail distribution of singular values in the
delta weights, we propose a delta quantization approach using mixed-precision.
This method employs higher-bit representation for singular vectors
corresponding to larger singular values. We evaluate our approach on various
fine-tuned LLMs, including math LLMs, code LLMs, chat LLMs, and even VLMs.
Experimental results demonstrate that our approach performs comparably to full
fine-tuned LLMs, surpassing both low-rank and low-bit baselines by a
considerable margin. Additionally, we show that our method is compatible with
various backbone LLMs, such as Llama-2, Llama-3, and Mistral, highlighting its
generalizability.
