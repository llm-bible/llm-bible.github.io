---
layout: publication
title: ALISA Accelerating Large Language Model Inference Via Sparsity45;aware KV Caching
authors: Zhao Youpeng, Wu Di, Wang Jun
conference: "Arxiv"
year: 2024
bibkey: zhao2024accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.17312"}
tags: ['Attention Mechanism', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
The Transformer architecture has significantly advanced natural language processing (NLP) and has been foundational in developing large language models (LLMs) such as LLaMA and OPT which have come to dominate a broad range of NLP tasks. Despite their superior accuracy LLMs present unique challenges in practical inference concerning the compute and memory45;intensive nature. Thanks to the autoregressive characteristic of LLM inference KV caching for the attention layers in Transformers can effectively accelerate LLM inference by substituting quadratic45;complexity computation with linear45;complexity memory accesses. Yet this approach requires increasing memory as demand grows for processing longer sequences. The overhead leads to reduced throughput due to I/O bottlenecks and even out45;of45;memory errors particularly on resource45;constrained systems like a single commodity GPU. In this paper we propose ALISA a novel algorithm45;system co45;design solution to address the challenges imposed by KV caching. On the algorithm level ALISA prioritizes tokens that are most important in generating a new token via a Sparse Window Attention (SWA) algorithm. SWA introduces high sparsity in attention layers and reduces the memory footprint of KV caching at negligible accuracy loss. On the system level ALISA employs three45;phase token45;level dynamical scheduling and optimizes the trade45;off between caching and recomputation thus maximizing the overall performance in resource45;constrained systems. In a single GPU45;CPU system we demonstrate that under varying workloads ALISA improves the throughput of baseline systems such as FlexGen and vLLM by up to 3X and 1.9X respectively.
