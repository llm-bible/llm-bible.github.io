---
layout: publication
title: 'Step Guided Reasoning: Improving Mathematical Reasoning Using Guidance Generation And Step Reasoning'
authors: Lang Cao, Chao Peng, Renhong Chen, Wu Ning, Yingtian Zou, Yitong Li
conference: "Arxiv"
year: 2024
bibkey: cao2024step
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.19817"}
tags: ['Fine-Tuning', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Few-Shot']
---
Mathematical reasoning has been challenging for large language models (LLMs).
However, the introduction of step-by-step Chain-of-Thought (CoT) inference has
significantly advanced the mathematical capabilities of LLMs. Despite this
progress, current approaches either necessitate extensive inference datasets
for training or depend on few-shot methods that frequently compromise
computational accuracy. To address these bottlenecks in mathematical reasoning,
we propose a novel method called Step Guidied Reasoning, which is more stable
and generalizable than few-shot methods and does not involve further
fine-tuning of the model. In this approach, LLMs reflect on small reasoning
steps, similar to how humans deliberate and focus attention on what to do next.
By incorporating this reflective process into the inference stage, LLMs can
effectively guide their reasoning from one step to the next. Through extensive
experiments, we demonstrate the significant effect of Step Guidied Reasoning in
augmenting mathematical performance in state-of-the-art language models.
Qwen2-72B-Instruct outperforms its math-specific counterpart,
Qwen2.5-72B-Math-Instruct, on MMLU- STEM with a score of 90.9%, compared to
87.3%. The average scores of Qwen2-7B-Instruct and Qwen2-72B-Instruct increase
from 27.1% to 36.3% and from 36.5% to 47.4% on the mathematics domain,
respectively.
