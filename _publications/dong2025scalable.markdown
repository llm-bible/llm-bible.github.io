---
layout: publication
title: 'Scalable LLM Math Reasoning Acceleration With Low-rank Distillation'
authors: Harry Dong, Bilge Acun, Beidi Chen, Yuejie Chi
conference: "Arxiv"
year: 2025
bibkey: dong2025scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.07861"}
tags: ['RAG', 'Training Techniques', 'Distillation', 'Efficiency and Optimization']
---
Due to long generations, large language model (LLM) math reasoning demands significant computational resources and time. While many existing efficient inference methods have been developed with excellent performance preservation on language tasks, they often severely degrade math performance. In this paper, we propose Caprese, a low-cost distillation method to recover lost capabilities from deploying efficient inference methods, focused primarily in feedforward blocks. With original weights unperturbed, roughly 1% of additional parameters, and only 20K synthetic training samples, we are able to recover much if not all of the math capabilities lost from efficient inference for thinking LLMs and without harm to language tasks for instruct LLMs. Moreover, Caprese slashes the number of active parameters (~2B cut for Gemma 2 9B and Llama 3.1 8B) and integrates cleanly into existing model layers to reduce latency (>11% reduction to generate 2048 tokens with Qwen 2.5 14B) while encouraging response brevity.
