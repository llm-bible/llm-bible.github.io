---
layout: publication
title: 'Coal Mining Question Answering With Llms'
authors: Antonio Carlos Rivera, Anthony Moore, Steven Robinson
conference: "Arxiv"
year: 2024
bibkey: rivera2024coal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.02959"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Prompting', 'Applications']
---
In this paper, we present a novel approach to coal mining question answering
(QA) using large language models (LLMs) combined with tailored prompt
engineering techniques. Coal mining is a complex, high-risk industry where
accurate, context-aware information is critical for safe and efficient
operations. Current QA systems struggle to handle the technical and dynamic
nature of mining-related queries. To address these challenges, we propose a
multi-turn prompt engineering framework designed to guide LLMs, such as GPT-4,
in answering coal mining questions with higher precision and relevance. By
breaking down complex queries into structured components, our approach allows
LLMs to process nuanced technical information more effectively. We manually
curated a dataset of 500 questions from real-world mining scenarios and
evaluated the system's performance using both accuracy (ACC) and GPT-4-based
scoring metrics. Experiments comparing ChatGPT, Claude2, and GPT-4 across
baseline, chain-of-thought (CoT), and multi-turn prompting methods demonstrate
that our method significantly improves both accuracy and contextual relevance,
with an average accuracy improvement of 15-18% and a notable increase in GPT-4
scores. The results show that our prompt-engineering approach provides a
robust, adaptable solution for domain-specific question answering in
high-stakes environments like coal mining.
