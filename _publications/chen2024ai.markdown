---
layout: publication
title: 'AI Can Be Cognitively Biased: An Exploratory Study On Threshold Priming In Llm-based Batch Relevance Assessment'
authors: Nuo Chen, Jiqun Liu, Xiaoyu Dong, Qijiong Liu, Tetsuya Sakai, Xiao-ming Wu
conference: "Arxiv"
year: 2024
bibkey: chen2024ai
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.16022"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Ethics and Bias', 'Fine-Tuning', 'Applications', 'Attention Mechanism']
---
Cognitive biases are systematic deviations in thinking that lead to
irrational judgments and problematic decision-making, extensively studied
across various fields. Recently, large language models (LLMs) have shown
advanced understanding capabilities but may inherit human biases from their
training data. While social biases in LLMs have been well-studied, cognitive
biases have received less attention, with existing research focusing on
specific scenarios. The broader impact of cognitive biases on LLMs in various
decision-making contexts remains underexplored. We investigated whether LLMs
are influenced by the threshold priming effect in relevance judgments, a core
task and widely-discussed research topic in the Information Retrieval (IR)
coummunity. The priming effect occurs when exposure to certain stimuli
unconsciously affects subsequent behavior and decisions. Our experiment
employed 10 topics from the TREC 2019 Deep Learning passage track collection,
and tested AI judgments under different document relevance scores, batch
lengths, and LLM models, including GPT-3.5, GPT-4, LLaMa2-13B and LLaMa2-70B.
Results showed that LLMs tend to give lower scores to later documents if
earlier ones have high relevance, and vice versa, regardless of the combination
and model used. Our finding demonstrates that LLM%u2019s judgments, similar to
human judgments, are also influenced by threshold priming biases, and suggests
that researchers and system engineers should take into account potential
human-like cognitive biases in designing, evaluating, and auditing LLMs in IR
tasks and beyond.
