---
layout: publication
title: 'Promptv: Leveraging Llm-powered Multi-agent Prompting For High-quality Verilog Generation'
authors: Zhendong Mi, Renming Zheng, Haowen Zhong, Yue Sun, Shaoyi Huang
conference: "Arxiv"
year: 2024
bibkey: mi2024leveraging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.11014'}
tags: ['Agentic', 'RAG', 'Model Architecture', 'Applications', 'Tools', 'Prompting']
---
Recent advances in agentic LLMs have demonstrated remarkable automated
Verilog code generation capabilities. However, existing approaches either
demand substantial computational resources or rely on LLM-assisted single-agent
prompt learning techniques, which we observe for the first time has a
degeneration issue - characterized by deteriorating generative performance and
diminished error detection and correction capabilities. This paper proposes a
novel multi-agent prompt learning framework to address these limitations and
enhance code generation quality. We show for the first time that multi-agent
architectures can effectively mitigate the degeneration risk while improving
code error correction capabilities, resulting in higher-quality Verilog code
generation. Experimental results show that the proposed method could achieve
96.4% and 96.5% pass@10 scores on VerilogEval Machine and Human benchmarks,
respectively while attaining 100% Syntax and 99.9% Functionality pass@5 metrics
on the RTLLM benchmark.
