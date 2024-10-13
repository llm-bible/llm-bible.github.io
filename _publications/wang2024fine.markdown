---
layout: publication
title: 'Fine-grained Self-endorsement Improves Factuality And Reasoning'
authors: Wang Ante, Song Linfeng, Peng Baolin, Tian Ye, Jin Lifeng, Mi Haitao, Su Jinsong, Yu Dong
conference: "Arxiv"
year: 2024
bibkey: wang2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15631"}
tags: ['Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Uncategorized']
---
This work studies improving large language model (LLM) generations at
inference time by mitigating fact-conflicting hallucinations. Particularly, we
propose a self-endorsement framework that leverages the fine-grained fact-level
comparisons across multiple sampled responses. Compared with prior ensemble
methods (Wang et al., 2022;Chen et al., 2023)) that perform response-level
selection, our approach can better alleviate hallucinations, especially for
longform generation tasks. Our approach can broadly benefit smaller and
open-source LLMs as it mainly conducts simple content-based comparisons.
Experiments on Biographies show that our method can effectively improve the
factuality of generations with simple and intuitive prompts across different
scales of LLMs. Besides, comprehensive analyses on TriviaQA and GSM8K
demonstrate the potential of self-endorsement for broader application.
