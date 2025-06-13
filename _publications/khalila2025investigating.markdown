---
layout: publication
title: 'Investigating Retrieval-augmented Generation In Quranic Studies: A Study Of 13 Open-source Large Language Models'
authors: Zahra Khalila, Arbi Haza Nasution, Winda Monika, Aytug Onan, Yohei Murakami, Yasir Bin Ismail Radi, Noor Mohammad Osmani
conference: "International Journal of Advanced Computer Science and Applications(IJACSA) 16(2) 2025"
year: 2025
bibkey: khalila2025investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.16581"}
tags: ['RAG', 'Model Architecture', 'Applications', 'Efficiency and Optimization']
---
Accurate and contextually faithful responses are critical when applying large
language models (LLMs) to sensitive and domain-specific tasks, such as
answering queries related to quranic studies. General-purpose LLMs often
struggle with hallucinations, where generated responses deviate from
authoritative sources, raising concerns about their reliability in religious
contexts. This challenge highlights the need for systems that can integrate
domain-specific knowledge while maintaining response accuracy, relevance, and
faithfulness. In this study, we investigate 13 open-source LLMs categorized
into large (e.g., Llama3:70b, Gemma2:27b, QwQ:32b), medium (e.g., Gemma2:9b,
Llama3:8b), and small (e.g., Llama3.2:3b, Phi3:3.8b). A Retrieval-Augmented
Generation (RAG) is used to make up for the problems that come with using
separate models. This research utilizes a descriptive dataset of Quranic surahs
including the meanings, historical context, and qualities of the 114 surahs,
allowing the model to gather relevant knowledge before responding. The models
are evaluated using three key metrics set by human evaluators: context
relevance, answer faithfulness, and answer relevance. The findings reveal that
large models consistently outperform smaller models in capturing query
semantics and producing accurate, contextually grounded responses. The
Llama3.2:3b model, even though it is considered small, does very well on
faithfulness (4.619) and relevance (4.857), showing the promise of smaller
architectures that have been well optimized. This article examines the
trade-offs between model size, computational efficiency, and response quality
while using LLMs in domain-specific applications.
