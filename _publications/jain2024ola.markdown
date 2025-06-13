---
layout: publication
title: 'OLA-VLM: Elevating Visual Perception In Multimodal Llms With Auxiliary Embedding Distillation'
authors: Jitesh Jain, Zhengyuan Yang, Humphrey Shi, Jianfeng Gao, Jianwei Yang
conference: "Arxiv"
year: 2024
bibkey: jain2024ola
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.09585"}
  - {name: "Code", url: "https://github.com/SHI-Labs/OLA-VLM"}
tags: ['Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Multimodal Models', 'Distillation']
---
The standard practice for developing contemporary MLLMs is to feed features
from vision encoder(s) into the LLM and train with natural language
supervision. In this work, we posit an overlooked opportunity to optimize the
intermediate LLM representations through a vision perspective (objective),
i.e., solely natural language supervision is sub-optimal for the MLLM's visual
understanding ability. To that end, we propose OLA-VLM, the first approach
distilling knowledge into the LLM's hidden representations from a set of target
visual representations. Firstly, we formulate the objective during the
pretraining stage in MLLMs as a coupled optimization of predictive visual
embedding and next text-token prediction. Secondly, we investigate MLLMs
trained solely with natural language supervision and identify a positive
correlation between the quality of visual representations within these models
and their downstream performance. Moreover, upon probing our OLA-VLM, we
observe improved representation quality owing to the embedding optimization.
Thirdly, we demonstrate that our OLA-VLM outperforms the single and
multi-encoder baselines, proving our approach's superiority over explicitly
feeding the corresponding features to the LLM. Particularly, OLA-VLM boosts
performance by an average margin of up to 2.5% on various benchmarks, with a
notable improvement of 8.7% on the Depth task in CV-Bench. Our code is
open-sourced at https://github.com/SHI-Labs/OLA-VLM .
