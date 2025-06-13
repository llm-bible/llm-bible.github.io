---
layout: publication
title: 'Self-boosting Large Language Models With Synthetic Preference Data'
authors: Qingxiu Dong, Li Dong, Xingxing Zhang, Zhifang Sui, Furu Wei
conference: "Arxiv"
year: 2024
bibkey: dong2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.06961"}
tags: ['Prompting', 'RAG', 'Tools', 'Reinforcement Learning']
---
Through alignment with human preferences, Large Language Models (LLMs) have
advanced significantly in generating honest, harmless, and helpful responses.
However, collecting high-quality preference data is a resource-intensive and
creativity-demanding process, especially for the continual improvement of LLMs.
We introduce SynPO, a self-boosting paradigm that leverages synthetic
preference data for model alignment. SynPO employs an iterative mechanism
wherein a self-prompt generator creates diverse prompts, and a response
improver refines model responses progressively. This approach trains LLMs to
autonomously learn the generative rewards for their own outputs and eliminates
the need for large-scale annotation of prompts and human preferences. After
four SynPO iterations, Llama3-8B and Mistral-7B show significant enhancements
in instruction-following abilities, achieving over 22.1% win rate improvements
on AlpacaEval 2.0 and ArenaHard. Simultaneously, SynPO improves the general
performance of LLMs on various tasks, validated by a 3.2 to 5.0 average score
increase on the well-recognized Open LLM leaderboard.
