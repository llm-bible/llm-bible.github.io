---
layout: publication
title: 'Halueval-wild: Evaluating Hallucinations Of Language Models In The Wild'
authors: Zhiying Zhu, Yiming Yang, Zhiqing Sun
conference: "Arxiv"
year: 2024
bibkey: zhu2024halueval
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.04307'}
  - {name: "Code", url: 'https://github.com/HaluEval-Wild/HaluEval-Wild'}
tags: ['Has Code', 'RAG', 'Security', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning']
---
Hallucinations pose a significant challenge to the reliability of large
language models (LLMs) in critical domains. Recent benchmarks designed to
assess LLM hallucinations within conventional NLP tasks, such as
knowledge-intensive question answering (QA) and summarization, are insufficient
for capturing the complexities of user-LLM interactions in dynamic, real-world
settings. To address this gap, we introduce HaluEval-Wild, the first benchmark
specifically designed to evaluate LLM hallucinations in the wild. We
meticulously collect challenging (adversarially filtered by Alpaca) user
queries from ShareGPT, an existing real-world user-LLM interaction datasets, to
evaluate the hallucination rates of various LLMs. Upon analyzing the collected
queries, we categorize them into five distinct types, which enables a
fine-grained analysis of the types of hallucinations LLMs exhibit, and
synthesize the reference answers with the powerful GPT-4 model and
retrieval-augmented generation (RAG). Our benchmark offers a novel approach
towards enhancing our comprehension of and improving LLM reliability in
scenarios reflective of real-world interactions. Our benchmark is available at
https://github.com/HaluEval-Wild/HaluEval-Wild.
