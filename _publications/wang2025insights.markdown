---
layout: publication
title: 'Insights From Verification: Training A Verilog Generation LLM With Reinforcement Learning With Testbench Feedback'
authors: Ning Wang, Bingkun Yao, Jie Zhou, Yuchen Hu, Xi Wang, Nan Guan, Zhe Jiang
conference: "Arxiv"
year: 2025
bibkey: wang2025insights
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.15804"}
  - {name: "Code", url: "https://anonymous.4open.science/r/VeriPrefer-E88B"}
tags: ['Agentic', 'Efficiency and Optimization', 'Applications', 'TACL', 'Reinforcement Learning', 'ACL', 'Training Techniques', 'Has Code']
---
Large language models (LLMs) have shown strong performance in Verilog
generation from natural language description. However, ensuring the functional
correctness of the generated code remains a significant challenge. This paper
introduces a method that integrates verification insights from testbench into
the training of Verilog generation LLMs, aligning the training with the
fundamental goal of hardware design: functional correctness. The main obstacle
in using LLMs for Verilog code generation is the lack of sufficient functional
verification data, particularly testbenches paired with design specifications
and code. To address this problem, we introduce an automatic testbench
generation pipeline that decomposes the process and uses feedback from the
Verilog compiler simulator (VCS) to reduce hallucination and ensure
correctness. We then use the testbench to evaluate the generated codes and
collect them for further training, where verification insights are introduced.
Our method applies reinforcement learning (RL), specifically direct preference
optimization (DPO), to align Verilog code generation with functional
correctness by training preference pairs based on testbench outcomes. In
evaluations on VerilogEval-Machine, VerilogEval-Human, RTLLM v1.1, RTLLM v2,
and VerilogEval v2, our approach consistently outperforms state-of-the-art
baselines in generating functionally correct Verilog code. We open source all
training code, data, and models at
https://anonymous.4open.science/r/VeriPrefer-E88B.
