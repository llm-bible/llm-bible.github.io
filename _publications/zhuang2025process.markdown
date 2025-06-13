---
layout: publication
title: 'Docpuzzle: A Process-aware Benchmark For Evaluating Realistic Long-context Reasoning Capabilities'
authors: Tianyi Zhuang, Chuqiao Kuang, Xiaoguang Li, Yihua Teng, Jihao Wu, Yasheng Wang, Lifeng Shang
conference: "Arxiv"
year: 2025
bibkey: zhuang2025process
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.17807"}
tags: ['Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Distillation', 'Ethics and Bias']
---
We present DocPuzzle, a rigorously constructed benchmark for evaluating
long-context reasoning capabilities in large language models (LLMs). This
benchmark comprises 100 expert-level QA problems requiring multi-step reasoning
over long real-world documents. To ensure the task quality and complexity, we
implement a human-AI collaborative annotation-validation pipeline. DocPuzzle
introduces an innovative evaluation framework that mitigates guessing bias
through checklist-guided process analysis, establishing new standards for
assessing reasoning capacities in LLMs. Our evaluation results show that:
1)Advanced slow-thinking reasoning models like o1-preview(69.7%) and
DeepSeek-R1(66.3%) significantly outperform best general instruct models like
Claude 3.5 Sonnet(57.7%); 2)Distilled reasoning models like
DeepSeek-R1-Distill-Qwen-32B(41.3%) falls far behind the teacher model,
suggesting challenges to maintain the generalization of reasoning capabilities
relying solely on distillation.
