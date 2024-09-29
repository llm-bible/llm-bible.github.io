---
layout: publication
title: Calibrating Llm45;based Evaluator
authors: Liu Yuxuan, Yang Tianchi, Huang Shaohan, Zhang Zihan, Huang Haizhen, Wei Furu, Deng Weiwei, Sun Feng, Zhang Qi
conference: "Arxiv"
year: 2023
bibkey: liu2023calibrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.13308"}
tags: ['Language Modeling', 'Prompting', 'RAG']
---
Recent advancements in large language models (LLMs) on language modeling and emergent capabilities make them a promising reference45;free evaluator of natural language generation quality and a competent alternative to human evaluation. However hindered by the closed45;source or high computational demand to host and tune there is a lack of practice to further calibrate an off45;the45;shelf LLM45;based evaluator towards better human alignment. In this work we propose AutoCalibrate a multi45;stage gradient45;free approach to automatically calibrate and align an LLM45;based evaluator toward human preference. Instead of explicitly modeling human preferences we first implicitly encompass them within a set of human labels. Then an initial set of scoring criteria is drafted by the language model itself leveraging in45;context learning on different few45;shot examples. To further calibrate this set of criteria we select the best performers and re45;draft them with self45;refinement. Our experiments on multiple text quality evaluation datasets illustrate a significant improvement in correlation with expert evaluation through calibration. Our comprehensive qualitative analysis conveys insightful intuitions and observations on the essence of effective scoring criteria.
