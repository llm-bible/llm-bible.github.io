---
layout: publication
title: 'Llms Are Globally Multilingual Yet Locally Monolingual: Exploring Knowledge Transfer Via Language And Thought Theory'
authors: Eojin Kang, Juae Kim
conference: "Arxiv"
year: 2025
bibkey: kang2025llms
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.24409'}
tags: ['RAG', 'Prompting', 'Training Techniques']
---
Multilingual large language models (LLMs) open up new possibilities for leveraging information across languages, but their factual knowledge recall remains inconsistent depending on the input language. While previous studies have attempted to address this issue through English-based prompting and evaluation, we explore non-English to English transfer via Language and Thought Theory. This perspective allows us to examine language-thought binding in LLMs and uncover why factual knowledge often fails to transfer effectively. We propose the Language-to-Thought (L2T) prompting strategy, which analyzes the relationship between input language, internal cognitive processes, and knowledge. Experimental results challenge the assumption that English-based approaches consistently outperform other languages and offer a novel insight that aligning the model's internal thought with the knowledge required for the task is critical for successful cross-lingual transfer. Furthermore, we show that applying L2T during training can alleviate LLMs' reliance on the input language and facilitate cross-linguistic knowledge integration without translation-based learning. Code and datasets will be available.
