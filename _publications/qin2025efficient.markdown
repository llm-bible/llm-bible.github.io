---
layout: publication
title: 'Reasoningv: Efficient Verilog Code Generation With Adaptive Hybrid Reasoning Model'
authors: Haiyan Qin, Zhiwei Xie, Jingjing Li, Liangchen Li, Xiaotong Feng, Junzhan Liu, Wang Kang
conference: "Arxiv"
year: 2025
bibkey: qin2025efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.14560'}
  - {name: "Code", url: 'https://github.com/BUAA-CLab/ReasoningV'}
tags: ['Has Code', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Large Language Models (LLMs) have advanced Verilog code generation
significantly, yet face challenges in data quality, reasoning capabilities, and
computational efficiency. This paper presents ReasoningV, a novel model
employing a hybrid reasoning strategy that integrates trained intrinsic
capabilities with dynamic inference adaptation for Verilog code generation. Our
framework introduces three complementary innovations: (1) ReasoningV-5K, a
high-quality dataset of 5,000 functionally verified instances with reasoning
paths created through multi-dimensional filtering of PyraNet samples; (2) a
two-stage training approach combining parameter-efficient fine-tuning for
foundational knowledge with full-parameter optimization for enhanced reasoning;
and (3) an adaptive reasoning mechanism that dynamically adjusts reasoning
depth based on problem complexity, reducing token consumption by up to 75%
while preserving performance. Experimental results demonstrate ReasoningV's
effectiveness with a pass@1 accuracy of 57.8% on VerilogEval-human, achieving
performance competitive with leading commercial models like Gemini-2.0-flash
(59.5%) and exceeding the previous best open-source model by 10.4 percentage
points. ReasoningV offers a more reliable and accessible pathway for advancing
AI-driven hardware design automation, with our model, data, and code available
at https://github.com/BUAA-CLab/ReasoningV.
