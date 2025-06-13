---
layout: publication
title: 'BOLT: Bootstrap Long Chain-of-thought In Language Models Without Distillation'
authors: Bo Pang, Hanze Dong, Jiacheng Xu, Silvio Savarese, Yingbo Zhou, Caiming Xiong
conference: "Arxiv"
year: 2025
bibkey: pang2025bootstrap
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.03860"}
tags: ['Tools', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs), such as o1 from OpenAI, have demonstrated
remarkable reasoning capabilities. o1 generates a long chain-of-thought
(LongCoT) before answering a question. LongCoT allows LLMs to analyze problems,
devise plans, reflect, and backtrack effectively. These actions empower LLM to
solve complex problems. After the release of o1, many teams have attempted to
replicate its LongCoT and reasoning capabilities. In terms of methods, they
primarily rely on knowledge distillation with data from existing models with
LongCoT capacities (e.g., OpenAI-o1, Qwen-QwQ, DeepSeek-R1-Preview), leaving
significant uncertainties on systematically developing such reasoning
abilities. In terms of data domains, these works focus narrowly on math while a
few others include coding, limiting their generalizability. This paper
introduces a novel approach to enable LLM's LongCoT capacity without
distillation from o1-like models or expensive human annotations, where we
bootstrap LongCoT (BOLT) from a standard instruct model. BOLT involves three
stages: 1) LongCoT data bootstrapping with in-context learning on a standard
instruct model; 2) LongCoT supervised finetuning; 3) online training to further
refine LongCoT capacities. In BOLT, only a few in-context examples need to be
constructed during the bootstrapping stage; in our experiments, we created 10
examples, demonstrating the feasibility of this approach. We use
Llama-3.1-70B-Instruct to bootstrap LongCoT and apply our method to various
model scales (7B, 8B, 70B). We achieve impressive performance on a variety of
benchmarks, Arena-Hard, MT-Bench, WildBench, ZebraLogic, MATH500, which
evaluate diverse task-solving and reasoning capabilities.
