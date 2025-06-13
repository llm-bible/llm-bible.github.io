---
layout: publication
title: 'Athena: Retrieval-augmented Legal Judgment Prediction With Large Language Models'
authors: Xiao Peng, Liang Chen
conference: "Arxiv"
year: 2024
bibkey: peng2024retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.11195"}
tags: ['Model Architecture', 'Few-Shot', 'Tools', 'Reinforcement Learning', 'RAG', 'In-Context Learning', 'GPT', 'Prompting', 'Applications', 'Attention Mechanism']
---
Recently, large language models (LLMs) like ChatGPT, LLaMA, and Claude have
prevailed in countless domains, including legal scenarios. With LLMs' rapid
technological progress, the development of prompt engineering (PE) as an
interface between the LLMs and real-world applications has drawn the attention
of all developers. Various PE methods have been proposed to overcome real-world
challenges, such as few-shot prompting, chain-of-thought, and
retrieval-augmented generation (RAG). However, RAG for legal judgment
prediction (LJP) is still underexplored. To address this, we propose "Athena",
a novel framework cultivating RAG as a core preprocess component to enhance
LLMs' performance on specialized tasks. Athena constructs a knowledge base for
accusations, attached with a semantic retrieval mechanism through
vectorization. Our experiments show that Athena's overall performance has
improved significantly, achieving state-of-the-art results on the CAIL2018
dataset. Our ablation study on the in-context window size parameter further
reproduces LLMs' "lost-in-the-middle" phenomenon with a relative positional
variation. And with moderate hyper-parameter-tuning, we can achieve at most 95%
of accuracy accordingly. We also study the impact of query rewriting and data
distribution, providing possible directions for future research based on former
analyses.
