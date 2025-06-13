---
layout: publication
title: 'Think Beyond Size: Adaptive Prompting For More Effective Reasoning'
authors: Kamesh R
conference: "Arxiv"
year: 2024
bibkey: r2024think
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.08130"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Few-Shot', 'Tools', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Pretrained large language models (LLMs) are increasingly utilized across a
wide range of natural language processing (NLP) tasks due to their impressive
capabilities as few-shot learners. Recent techniques, such as chain-of-thought
(CoT) prompting, have significantly advanced multi-step reasoning by
introducing step-by-step decomposition, achieving state-of-the-art results on
complex reasoning benchmarks. However, these approaches often rely on static
prompting templates that do not adapt to task complexity or errors during the
reasoning process. In this work, we introduce Adaptive Prompting, a dynamic and
iterative framework designed to enhance reasoning by incorporating real-time
adjustments to prompt structures and validation mechanisms.Experimental results
demonstrate that Adaptive Prompting significantly improves performance on
diverse reasoning benchmarks, including arithmetic reasoning (GSM8K,
MultiArith), logical reasoning and commonsense tasks, achieving substantial
accuracy gains compared to static prompting baselines. By integrating guided
prompts, intermediate validation, and self-corrective steps, our approach
enables smaller models to achieve competitive performance with larger
counterparts, such as GPT-4, while maintaining computational efficiency. The
framework achieves this without requiring fine-tuning or task-specific training
data, highlighting the untapped potential of iterative reasoning methods.
