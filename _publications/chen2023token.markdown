---
layout: publication
title: 'Token Prediction As Implicit Classification To Identify Llm-generated Text'
authors: Yutian Chen, Hao Kang, Vivian Zhai, Liangze Li, Rita Singh, Bhiksha Raj
conference: "Arxiv"
year: 2023
bibkey: chen2023token
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.08723'}
tags: ['Language Modeling', 'Interpretability and Explainability', 'Transformer', 'Efficiency and Optimization', 'GPT', 'Model Architecture', 'Applications', 'Pretraining Methods']
---
This paper introduces a novel approach for identifying the possible large
language models (LLMs) involved in text generation. Instead of adding an
additional classification layer to a base LM, we reframe the classification
task as a next-token prediction task and directly fine-tune the base LM to
perform it. We utilize the Text-to-Text Transfer Transformer (T5) model as the
backbone for our experiments. We compared our approach to the more direct
approach of utilizing hidden states for classification. Evaluation shows the
exceptional performance of our method in the text classification task,
highlighting its simplicity and efficiency. Furthermore, interpretability
studies on the features extracted by our model reveal its ability to
differentiate distinctive writing styles among various LLMs even in the absence
of an explicit classifier. We also collected a dataset named OpenLLMText,
containing approximately 340k text samples from human and LLMs, including
GPT3.5, PaLM, LLaMA, and GPT2.
