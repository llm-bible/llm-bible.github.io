---
layout: publication
title: 'TRAPDOC: Deceiving LLM Users By Injecting Imperceptible Phantom Tokens Into Documents'
authors: Hyundong Jin, Sicheol Sung, Shinwoo Park, Seungyeop Baik, Yo-sub Han
conference: "Arxiv"
year: 2025
bibkey: jin2025deceiving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.00089'}
  - {name: "Code", url: 'https://github.com/jindong22/TrapDoc'}
tags: ['Has Code', 'Tools', 'Merging']
---
The reasoning, writing, text-editing, and retrieval capabilities of proprietary large language models (LLMs) have advanced rapidly, providing users with an ever-expanding set of functionalities. However, this growing utility has also led to a serious societal concern: the over-reliance on LLMs. In particular, users increasingly delegate tasks such as homework, assignments, or the processing of sensitive documents to LLMs without meaningful engagement. This form of over-reliance and misuse is emerging as a significant social issue. In order to mitigate these issues, we propose a method injecting imperceptible phantom tokens into documents, which causes LLMs to generate outputs that appear plausible to users but are in fact incorrect. Based on this technique, we introduce TRAPDOC, a framework designed to deceive over-reliant LLM users. Through empirical evaluation, we demonstrate the effectiveness of our framework on proprietary LLMs, comparing its impact against several baselines. TRAPDOC serves as a strong foundation for promoting more responsible and thoughtful engagement with language models. Our code is available at https://github.com/jindong22/TrapDoc.
