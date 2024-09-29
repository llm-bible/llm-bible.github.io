---
layout: publication
title: 'Llm-aided Compilation For Tensor Accelerators'
authors: Hong Charles, Bhatia Sahil, Haan Altan, Dong Shengjun Kris, Nikiforov Dima, Cheung Alvin, Shao Yakun Sophia
conference: "Arxiv"
year: 2024
bibkey: hong2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03408"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
Hardware accelerators in particular accelerators for tensor processing have many potential application domains. However they currently lack the software infrastructure to support the majority of domains outside of deep learning. Furthermore a compiler that can easily be updated to reflect changes at both application and hardware levels would enable more agile development and design space exploration of accelerators allowing hardware designers to realize closer-to-optimal performance. In this work we discuss how large language models (LLMs) could be leveraged to build such a compiler. Specifically we demonstrate the ability of GPT-4 to achieve high pass rates in translating code to the Gemmini accelerator and prototype a technique for decomposing translation into smaller more LLM-friendly steps. Additionally we propose a 2-phase workflow for utilizing LLMs to generate hardware-optimized code.
