---
layout: publication
title: Calibrating Llm-based Evaluator
authors: Liu Yuxuan, Yang Tianchi, Huang Shaohan, Zhang Zihan, Huang Haizhen, Wei Furu, Deng Weiwei, Sun Feng, Zhang Qi
conference: "Arxiv"
year: 2023
bibkey: liu2023calibrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.13308"}
tags: ['Few Shot', 'In Context Learning', 'Language Modeling', 'Prompting', 'RAG']
---
Recent advancements in large language models (LLMs) on language modeling and emergent capabilities make them a promising reference-free evaluator of natural language generation quality and a competent alternative to human evaluation. However hindered by the closed-source or high computational demand to host and tune there is a lack of practice to further calibrate an off-the-shelf LLM-based evaluator towards better human alignment. In this work we propose AutoCalibrate a multi-stage gradient-free approach to automatically calibrate and align an LLM-based evaluator toward human preference. Instead of explicitly modeling human preferences we first implicitly encompass them within a set of human labels. Then an initial set of scoring criteria is drafted by the language model itself leveraging in-context learning on different few-shot examples. To further calibrate this set of criteria we select the best performers and re-draft them with self-refinement. Our experiments on multiple text quality evaluation datasets illustrate a significant improvement in correlation with expert evaluation through calibration. Our comprehensive qualitative analysis conveys insightful intuitions and observations on the essence of effective scoring criteria.
