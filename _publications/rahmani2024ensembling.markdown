---
layout: publication
title: 'Judgeblender: Ensembling Judgments For Automatic Relevance Assessment'
authors: Hossein A. Rahmani, Emine Yilmaz, Nick Craswell, Bhaskar Mitra
conference: "Arxiv"
year: 2024
bibkey: rahmani2024ensembling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.13268"}
tags: ['Tools', 'GPT', 'Ethics and Bias', 'RAG', 'Model Architecture', 'Training Techniques', 'Prompting']
---
The effective training and evaluation of retrieval systems require a
substantial amount of relevance judgments, which are traditionally collected
from human assessors -- a process that is both costly and time-consuming. Large
Language Models (LLMs) have shown promise in generating relevance labels for
search tasks, offering a potential alternative to manual assessments. Current
approaches often rely on a single LLM, such as GPT-4, which, despite being
effective, are expensive and prone to intra-model biases that can favour
systems leveraging similar models. In this work, we introduce JudgeBlender, a
framework that employs smaller, open-source models to provide relevance
judgments by combining evaluations across multiple LLMs (LLMBlender) or
multiple prompts (PromptBlender). By leveraging the LLMJudge benchmark [18], we
compare JudgeBlender with state-of-the-art methods and the top performers in
the LLMJudge challenge. Our results show that JudgeBlender achieves competitive
performance, demonstrating that very large models are often unnecessary for
reliable relevance assessments.
