---
layout: publication
title: 'Understanding Multimodal Llms: The Mechanistic Interpretability Of Llava In Visual Question Answering'
authors: Zeping Yu, Sophia Ananiadou
conference: "Arxiv"
year: 2024
bibkey: yu2024understanding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.10950'}
  - {name: "Code", url: 'https://github.com/zepingyu0512/llava-mechanism'}
tags: ['Has Code', 'Interpretability and Explainability', 'Applications', 'Prompting', 'Multimodal Models', 'Reinforcement Learning', 'In-Context Learning']
---
Understanding the mechanisms behind Large Language Models (LLMs) is crucial
for designing improved models and strategies. While recent studies have yielded
valuable insights into the mechanisms of textual LLMs, the mechanisms of
Multi-modal Large Language Models (MLLMs) remain underexplored. In this paper,
we apply mechanistic interpretability methods to analyze the visual question
answering (VQA) mechanisms in the first MLLM, Llava. We compare the mechanisms
between VQA and textual QA (TQA) in color answering tasks and find that: a) VQA
exhibits a mechanism similar to the in-context learning mechanism observed in
TQA; b) the visual features exhibit significant interpretability when
projecting the visual embeddings into the embedding space; and c) Llava
enhances the existing capabilities of the corresponding textual LLM Vicuna
during visual instruction tuning. Based on these findings, we develop an
interpretability tool to help users and researchers identify important visual
locations for final predictions, aiding in the understanding of visual
hallucination. Our method demonstrates faster and more effective results
compared to existing interpretability approaches. Code:
\url\{https://github.com/zepingyu0512/llava-mechanism\}
