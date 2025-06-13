---
layout: publication
title: 'Codingteachllm: Empowering Llm''s Coding Ability Via AST Prior Knowledge'
authors: Zhangquan Chen, Chunjiang Liu, Haobin Duan
conference: "Arxiv"
year: 2024
bibkey: chen2024empowering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.15426"}
tags: ['Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
In this paper, we introduce CodingTeachLLM, a large language model (LLM)
designed for coding teaching. Specially, we aim to enhance the coding ability
of LLM and lead it to better teaching mode in education context. Thus, we
propose an end-to-end prior-based three-phases supervised fine-tuned model,
which is proved more competitive than traditional fine-tuning method. More
specifically, our model realizes the structural disassembly and incremental
guided output of educational knowledge. To this end, we robustify data
classification of three types via a sampler and overlap estimation neural
network, and inject the preprocessing datasets into pre-trained model in three
batches for LORA fine-tuning. Then, we design a prior module couples system
prompt, vector databases, and abstract syntax tree task segmentation. Finally,
the compression method and regularization constraint are applied to the
prior-based fine-tuned model, followed by text filter at the output end to
obtain incremental guided results. Our model represents the first research
effort to truly embody the tutor role with the features of abundant educational
knowledge, step-by-step incremental guided outputs and non-disclosure of
answers. Extensive experiments report that our model also achieves
state-of-the-art in code abilities compared to open-source models, reaching an
impressive 75.10% on the HumanEval (@pass 1) benchmark. Additionally, our model
maintains strong conversational capabilities, with the 13B quantized version
achieving scores of 56.34, 50.60, and 45.27 respectively on the MMLU, C-Eval,
and AGIEval (5 shot) dialogue evaluation benchmarks.
