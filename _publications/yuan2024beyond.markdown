---
layout: publication
title: Beyond Under45;alignment Atomic Preference Enhanced Factuality Tuning For Large Language Models
authors: Yuan Hongbang, Chen Yubo, Cao Pengfei, Jin Zhuoran, Liu Kang, Zhao Jun
conference: "Arxiv"
year: 2024
bibkey: yuan2024beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12416"}
tags: ['Pretraining Methods', 'RAG', 'Tools']
---
Large language models (LLMs) have achieved remarkable success but still tend to generate factually erroneous responses a phenomenon known as hallucination. A recent trend is to use preference learning to fine45;tune models to align with factuality. However existing work primarily evaluates fine45;tuned models on in45;domain (ID) datasets and the factuality on out45;of45;domain (OOD) datasets remains underexplored. In this paper we conduct a comprehensive evaluation of the factuality of different models tuned by various preference learning algorithms and demonstrate that their performance on OOD datasets either increases minimally or decreases. Subsequently we reveal that the main cause of models failure to uphold factuality under a distribution shift is textbf123;under45;alignment125; rather than textbf123;over45;alignment125; by analyzing the token distribution shift of the models before and after tuning. Finally we propose textbf123;APEFT125; (textbf123;A125;tomic textbf123;P125;reference textbf123;E125;nhanced textbf123;F125;actuality textbf123;T125;uning) a framework that enhances models awareness of factuality at the granularity of individual facts. Extensive experiments demonstrate that APEFT improves model performance by an average of boldsymbol123;3.4537;125; on both ID and OOD datasets which is highly effective.
