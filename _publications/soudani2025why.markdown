---
layout: publication
title: 'Why Uncertainty Estimation Methods Fall Short In RAG: An Axiomatic Analysis'
authors: Heydar Soudani, Evangelos Kanoulas, Faegheh Hasibi
conference: "Arxiv"
year: 2025
bibkey: soudani2025why
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.07459"}
tags: ['RAG', 'Tools', 'Prompting']
---
Large Language Models (LLMs) are valued for their strong performance across various tasks, but they also produce inaccurate or misleading outputs. Uncertainty Estimation (UE) quantifies the model's confidence and helps users assess response reliability. However, existing UE methods have not been thoroughly examined in scenarios like Retrieval-Augmented Generation (RAG), where the input prompt includes non-parametric knowledge. This paper shows that current UE methods cannot reliably assess correctness in the RAG setting. We further propose an axiomatic framework to identify deficiencies in existing methods and guide the development of improved approaches. Our framework introduces five constraints that an effective UE method should meet after incorporating retrieved documents into the LLM's prompt. Experimental results reveal that no existing UE method fully satisfies all the axioms, explaining their suboptimal performance in RAG. We further introduce a simple yet effective calibration function based on our framework, which not only satisfies more axioms than baseline methods but also improves the correlation between uncertainty estimates and correctness.
