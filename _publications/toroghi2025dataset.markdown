---
layout: publication
title: 'Colota: A Dataset For Entity-based Commonsense Reasoning Over Long-tail Knowledge'
authors: Armin Toroghi, Willis Guo, Scott Sanner
conference: "Arxiv"
year: 2025
bibkey: toroghi2025dataset
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.14462'}
tags: ['Reinforcement Learning', 'Security', 'Applications']
---
The rise of Large Language Models (LLMs) has redefined the AI landscape,
particularly due to their ability to encode factual and commonsense knowledge,
and their outstanding performance in tasks requiring reasoning. Despite these
advances, hallucinations and reasoning errors remain a significant barrier to
their deployment in high-stakes settings. In this work, we observe that even
the most prominent LLMs, such as OpenAI-o1, suffer from high rates of reasoning
errors and hallucinations on tasks requiring commonsense reasoning over
obscure, long-tail entities. To investigate this limitation, we present a new
dataset for Commonsense reasoning over Long-Tail entities (CoLoTa), that
consists of 3,300 queries from question answering and claim verification tasks
and covers a diverse range of commonsense reasoning skills. We remark that
CoLoTa can also serve as a Knowledge Graph Question Answering (KGQA) dataset
since the support of knowledge required to answer its queries is present in the
Wikidata knowledge graph. However, as opposed to existing KGQA benchmarks that
merely focus on factoid questions, our CoLoTa queries also require commonsense
reasoning. Our experiments with strong LLM-based KGQA methodologies indicate
their severe inability to answer queries involving commonsense reasoning.
Hence, we propose CoLoTa as a novel benchmark for assessing both (i) LLM
commonsense reasoning capabilities and their robustness to hallucinations on
long-tail entities and (ii) the commonsense reasoning capabilities of KGQA
methods.
