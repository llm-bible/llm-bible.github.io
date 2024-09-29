---
layout: publication
title: Making Pre45;trained Language Models Better Few45;shot Learners
authors: Tianyu Gao, Adam Fisch, Danqi Chen
conference: "Arxiv"
year: 2020
bibkey: gao2020making
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2012.15723v2"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG']
---
The recent GPT45;3 model (Brown et al. 2020) achieves remarkable few45;shot performance solely by leveraging a natural45;language prompt and a few task demonstrations as input context. Inspired by their findings we study few45;shot learning in a more practical scenario where we use smaller language models for which fine45;tuning is computationally efficient. We present LM45;BFF45;45;better few45;shot fine45;tuning of language models45;45;a suite of simple and complementary techniques for fine45;tuning language models on a small number of annotated examples. Our approach includes (1) prompt45;based fine45;tuning together with a novel pipeline for automating prompt generation; and (2) a refined strategy for dynamically and selectively incorporating demonstrations into each context. Finally we present a systematic evaluation for analyzing few45;shot performance on a range of NLP tasks including classification and regression. Our experiments demonstrate that our methods combine to dramatically outperform standard fine45;tuning procedures in this low resource setting achieving up to 3037; absolute improvement and 1137; on average across all tasks. Our approach makes minimal assumptions on task resources and domain expertise and hence constitutes a strong task45;agnostic method for few45;shot learning.
