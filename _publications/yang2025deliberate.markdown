---
layout: publication
title: 'Deepcritic: Deliberate Critique With Large Language Models'
authors: Wenkai Yang, Jingwen Chen, Yankai Lin, Ji-rong Wen
conference: "Arxiv"
year: 2025
bibkey: yang2025deliberate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.00662"}
tags: ['Fine-Tuning', 'Agentic', 'GPT', 'Tools', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
As Large Language Models (LLMs) are rapidly evolving, providing accurate
feedback and scalable oversight on their outputs becomes an urgent and critical
problem. Leveraging LLMs as critique models to achieve automated supervision is
a promising solution. In this work, we focus on studying and enhancing the math
critique ability of LLMs. Current LLM critics provide critiques that are too
shallow and superficial on each step, leading to low judgment accuracy and
struggling to offer sufficient feedback for the LLM generator to correct
mistakes. To tackle this issue, we propose a novel and effective two-stage
framework to develop LLM critics that are capable of deliberately critiquing on
each reasoning step of math solutions. In the first stage, we utilize
Qwen2.5-72B-Instruct to generate 4.5K long-form critiques as seed data for
supervised fine-tuning. Each seed critique consists of deliberate step-wise
critiques that includes multi-perspective verifications as well as in-depth
critiques of initial critiques for each reasoning step. Then, we perform
reinforcement learning on the fine-tuned model with either existing
human-labeled data from PRM800K or our automatically annotated data obtained
via Monte Carlo sampling-based correctness estimation, to further incentivize
its critique ability. Our developed critique model built on Qwen2.5-7B-Instruct
not only significantly outperforms existing LLM critics (including the
same-sized DeepSeek-R1-distill models and GPT-4o) on various error
identification benchmarks, but also more effectively helps the LLM generator
refine erroneous steps through more detailed feedback.
