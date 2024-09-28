---
layout: publication
title: AutoVCoder A Systematic Framework for Automated Verilog Code Generation using LLMs
authors: Gao Mingzhe, Zhao Jieru, Lin Zhe, Ding Wenchao, Hou Xiaofeng, Feng Yu, Li Chao, Guo Minyi
conference: "Arxiv"
year: 2024
bibkey: gao2024autovcoder
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.18333"}
tags: ['ARXIV', 'Applications', 'Fine Tuning', 'LLM', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
Recently the use of large language models (LLMs) for software code generation e.g. C/C++ and Python has proven a great success. However LLMs still suffer from low syntactic and functional correctness when it comes to the generation of register-transfer level (RTL) code such as Verilog. To address this issue in this paper we develop AutoVCoder a systematic open-source framework that significantly improves the LLMs correctness of generating Verilog code and enhances the quality of its output at the same time. Our framework integrates three novel techniques including a high-quality hardware dataset generation approach a two-round LLM fine-tuning method and a domain-specific retrieval-augmented generation (RAG) mechanism. Experimental results demonstrate that AutoVCoder outperforms both industrial and academic LLMs in Verilog code generation. Specifically AutoVCoder shows a 0.5 and 2.2 improvement in functional correctness on the EvalMachine and EvalHuman benchmarks compared with BetterV and also achieves a 3.4 increase in syntax correctness and a 3.4 increase in functional correctness on the RTLLM benchmark compared with RTLCoder.
