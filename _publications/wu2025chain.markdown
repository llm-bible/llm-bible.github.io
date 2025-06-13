---
layout: publication
title: 'Chain-of-tools: Utilizing Massive Unseen Tools In The Cot Reasoning Of Frozen Language Models'
authors: Mengsong Wu, Tong Zhu, Han Han, Xiang Zhang, Wenbiao Shao, Wenliang Chen
conference: "Arxiv"
year: 2025
bibkey: wu2025chain
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.16779'}
  - {name: "Code", url: 'https://github.com/fairyshine/Chain-of-Tools'}
tags: ['Has Code', 'Interpretability and Explainability', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Tools', 'Prompting', 'Interpretability']
---
Tool learning can further broaden the usage scenarios of large language
models (LLMs). However most of the existing methods either need to finetune
that the model can only use tools seen in the training data, or add tool
demonstrations into the prompt with lower efficiency. In this paper, we present
a new Tool Learning method Chain-of-Tools. It makes full use of the powerful
semantic representation capability of frozen LLMs to finish tool calling in CoT
reasoning with a huge and flexible tool pool which may contain unseen tools.
Especially, to validate the effectiveness of our approach in the massive unseen
tool scenario, we construct a new dataset SimpleToolQuestions. We conduct
experiments on two numerical reasoning benchmarks (GSM8K-XL and FuncQA) and two
knowledge-based question answering benchmarks (KAMEL and SimpleToolQuestions).
Experimental results show that our approach performs better than the baseline.
We also identify dimensions of the model output that are critical in tool
selection, enhancing the model interpretability. Our code and data are
available at: https://github.com/fairyshine/Chain-of-Tools .
