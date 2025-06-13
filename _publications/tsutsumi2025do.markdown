---
layout: publication
title: 'Do Large Language Models Know Folktales? A Case Study Of Yokai In Japanese Folktales'
authors: Ayuto Tsutsumi, Yuu Jinnai
conference: "Arxiv"
year: 2025
bibkey: tsutsumi2025do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.03619"}
  - {name: "Code", url: "https://github.com/CyberAgentA"}
tags: ['Agentic', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Although Large Language Models (LLMs) have demonstrated strong language understanding and generation abilities across various languages, their cultural knowledge is often limited to English-speaking communities, which can marginalize the cultures of non-English communities. To address the problem, evaluation of the cultural awareness of the LLMs and the methods to develop culturally aware LLMs have been investigated. In this study, we focus on evaluating knowledge of folktales, a key medium for conveying and circulating culture. In particular, we focus on Japanese folktales, specifically on knowledge of Yokai. Yokai are supernatural creatures originating from Japanese folktales that continue to be popular motifs in art and entertainment today. Yokai have long served as a medium for cultural expression, making them an ideal subject for assessing the cultural awareness of LLMs. We introduce YokaiEval, a benchmark dataset consisting of 809 multiple-choice questions (each with four options) designed to probe knowledge about yokai. We evaluate the performance of 31 Japanese and multilingual LLMs on this dataset. The results show that models trained with Japanese language resources achieve higher accuracy than English-centric models, with those that underwent continued pretraining in Japanese, particularly those based on Llama-3, performing especially well. The code and dataset are available at https://github.com/CyberAgentA ILab/YokaiEval.
