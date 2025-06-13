---
layout: publication
title: 'Verbosity-aware Rationale Reduction: Effective Reduction Of Redundant Rationale Via Principled Criteria'
authors: Joonwon Jang, Jaehee Kim, Wonbin Kweon, Seonghyeon Lee, Hwanjo Yu
conference: "Arxiv"
year: 2024
bibkey: jang2024verbosity
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.21006'}
tags: ['RAG', 'Tools']
---
Large Language Models (LLMs) rely on generating extensive intermediate reasoning units (e.g., tokens, sentences) to enhance final answer quality across a wide range of complex tasks. While this approach has proven effective, it inevitably increases substantial inference costs. Previous methods adopting token-level reduction without clear criteria result in poor performance compared to models trained with complete rationale. To address this challenge, we propose a novel sentence-level rationale reduction framework leveraging likelihood-based criteria, verbosity, to identify and remove redundant reasoning sentences. Unlike previous approaches, our method leverages verbosity to selectively remove redundant reasoning sentences while preserving reasoning capabilities. Our experimental results across various reasoning tasks demonstrate that our method improves performance by an average of 7.71% while reducing token generation by 19.87% compared to model trained with complete reasoning paths.
