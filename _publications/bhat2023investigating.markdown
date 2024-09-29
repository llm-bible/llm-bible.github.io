---
layout: publication
title: Investigating Answerability of LLMs for Long-Form Question Answering
authors: Bhat Meghana Moorthy, Meng Rui, Liu Ye, Zhou Yingbo, Yavuz Semih
conference: "Arxiv"
year: 2023
bibkey: bhat2023investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.08210"}
tags: ['Applications', 'GPT', 'Model Architecture']
---
As we embark on a new era of LLMs it becomes increasingly crucial to understand their capabilities limitations and differences. Toward making further progress in this direction we strive to build a deeper understanding of the gaps between massive LLMs (e.g. ChatGPT) and smaller yet effective open-source LLMs and their distilled counterparts. To this end we specifically focus on long-form question answering (LFQA) because it has several practical and impactful applications (e.g. troubleshooting customer service etc.) yet is still understudied and challenging for LLMs. We propose a question-generation method from abstractive summaries and show that generating follow-up questions from summaries of long documents can create a challenging setting for LLMs to reason and infer from long contexts. Our experimental results confirm that (1) our proposed method of generating questions from abstractive summaries pose a challenging setup for LLMs and shows performance gaps between LLMs like ChatGPT and open-source LLMs (Alpaca Llama) (2) open-source LLMs exhibit decreased reliance on context for generated questions from the original document but their generation capabilities drop significantly on generated questions from summaries -- especially for longer contexts (1024 tokens)
