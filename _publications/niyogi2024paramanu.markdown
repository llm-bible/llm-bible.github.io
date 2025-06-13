---
layout: publication
title: 'PARAMANU-GANITA: Can Small Math Language Models Rival With Large Language Models On Mathematical Reasoning?'
authors: Mitodru Niyogi, Arnab Bhattacharya
conference: "Arxiv"
year: 2024
bibkey: niyogi2024paramanu
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.14395"}
  - {name: "Code", url: "https://huggingface.co/gyanai/paramanu-ganita-208M-hf"}
tags: ['Pretraining Methods', 'Training Techniques', 'Fine-Tuning', 'Has Code']
---
In this paper, we study whether domain specific pretraining of small
generative language models (SLM) from scratch with domain specialized tokenizer
and Chain-of-Thought (CoT) instruction fine-tuning results in competitive
performance on mathematical reasoning compared to LLMs? Secondly, whether this
approach is environmentally sustainable, highly cost efficient? To address
these research questions, we present Paramanu-Ganita, a 208 million-parameter
novel decoder-only Auto Regressive SLM on mathematics. We performed pretraining
from scratch on 31.5 billion tokens for 170 A100 hours using a context size of
4096 on a mixed mathematical corpus consisting of web pages, source code,
textbooks, CoT templatised StackOverflow QA pairs, and mathematical lecture
notes in LaTeX curated by us. We also trained a math and code specialised BPE
tokenizer. We proposed and performed CoT instruction fine-tuning of
Paramanu-Ganita on the MetaMathQA dataset. Our model Paramanu-Ganita, despite
being 34 times smaller than the 7B LLMs, outperforms generalist LLMs by
approximately 30% points, and even math-specialised LLMs by 3-23% points in
GSM8K test accuracy metric. On MATH benchmark, Paramanu-Ganita outperformed the
various models by 6-8% points. On benchmarks like LogiQA, MMLU (high school,
college level), and competitive exams level, AGIEVAL (AQuA-RAT, SAT-Math),
Paramanu-Ganita outperformed others by 1-4%. Our model is available at
https://huggingface.co/gyanai/paramanu-ganita-208M-hf .
