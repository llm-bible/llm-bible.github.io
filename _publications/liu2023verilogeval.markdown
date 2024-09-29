---
layout: publication
title: Verilogeval Evaluating Large Language Models For Verilog Code Generation
authors: Liu Mingjie, Pinckney Nathaniel, Khailany Brucek, Ren Haoxing
conference: "Arxiv"
year: 2023
bibkey: liu2023verilogeval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.07544"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
The increasing popularity of large language models (LLMs) has paved the way for their application in diverse domains. This paper proposes a benchmarking framework tailored specifically for evaluating LLM performance in the context of Verilog code generation for hardware design and verification. We present a comprehensive evaluation dataset consisting of 156 problems from the Verilog instructional website HDLBits. The evaluation set consists of a diverse set of Verilog code generation tasks ranging from simple combinational circuits to complex finite state machines. The Verilog code completions can be automatically tested for functional correctness by comparing the transient simulation outputs of the generated design with a golden solution. We also demonstrate that the Verilog code generation capability of pretrained language models could be improved with supervised fine-tuning by bootstrapping with LLM generated synthetic problem-code pairs.
