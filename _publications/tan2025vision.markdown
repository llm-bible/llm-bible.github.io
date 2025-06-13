---
layout: publication
title: 'Vision Llms Are Bad At Hierarchical Visual Understanding, And Llms Are The Bottleneck'
authors: Yuwen Tan, Yuan Qing, Boqing Gong
conference: "Arxiv"
year: 2025
bibkey: tan2025vision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24840"}
tags: ['Applications', 'Reinforcement Learning']
---
This paper reveals that many state-of-the-art large language models (LLMs) lack hierarchical knowledge about our visual world, unaware of even well-established biology taxonomies. This shortcoming makes LLMs a bottleneck for vision LLMs' hierarchical visual understanding (e.g., recognizing Anemone Fish but not Vertebrate). We arrive at these findings using about one million four-choice visual question answering (VQA) tasks constructed from six taxonomies and four image datasets. Interestingly, finetuning a vision LLM using our VQA tasks reaffirms LLMs' bottleneck effect to some extent because the VQA tasks improve the LLM's hierarchical consistency more than the vision LLM's. We conjecture that one cannot make vision LLMs understand visual concepts fully hierarchical until LLMs possess corresponding taxonomy knowledge.
