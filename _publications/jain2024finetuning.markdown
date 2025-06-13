---
layout: publication
title: 'First: Finetuning Router-selective Transformers For Input-adaptive Latency Reduction'
authors: Akriti Jain, Saransh Sharma, Koyel Mukherjee, Soumyabrata Pal
conference: "Arxiv"
year: 2024
bibkey: jain2024finetuning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12513"}
tags: ['Transformer', 'Tools', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Prompting']
---
Auto-regressive Large Language Models (LLMs) demonstrate remarkable
performance across different domains such as vision and language processing.
However, due to sequential processing through a stack of transformer layers,
autoregressive decoding faces significant computation/latency challenges,
particularly in resource-constrained environments like mobile and edge devices.
Existing approaches in literature that aim to improve latency via skipping
layers have two distinct flavors - 1) Early exit, and 2) Input-agnostic
heuristics where tokens exit at pre-determined layers irrespective of input
sequence. Both the above strategies have limitations - the former cannot be
applied to handle KV Caching necessary for speed-ups in modern framework and
the latter does not capture the variation in layer importance across tasks or
more generally, across input sequences. To address both limitations, we propose
FiRST, an algorithm that reduces inference latency by using layer-specific
routers to select a subset of transformer layers adaptively for each input
sequence - the prompt (during the prefill stage) decides which layers will be
skipped during decoding. FiRST preserves compatibility with KV caching enabling
faster inference while being quality-aware. FiRST is model-agnostic and can be
easily enabled on any pre-trained LLM. Our approach reveals that input
adaptivity is critical - indeed, different task-specific middle layers play a
crucial role in evolving hidden representations depending on tasks. Extensive
experiments show that FiRST significantly reduces latency while outperforming
other layer selection strategies in quality metics. It retains competitive
performance to base model (without layer skipping) and in some cases, even
improves upon it. FiRST is thus a promising and efficient solution for LLM
deployment in low-resource environments.
