---
layout: publication
title: 'Wrapper Boxes: Faithful Attribution Of Model Predictions To Training Data'
authors: Yiheng Su, Junyi Jessy Li, Matthew Lease
conference: "The seventh edition of BlackboxNLP Workshop at EMNLP 2024"
year: 2023
bibkey: su2023wrapper
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08644"}
  - {name: "Code", url: "https://github.com/SamSoup/WrapperBox"}
tags: ['Applications', 'Interpretability and Explainability', 'RAG', 'Training Techniques', 'Has Code']
---
Can we preserve the accuracy of neural models while also providing faithful
explanations of model decisions to training data? We propose a "wrapper box''
pipeline: training a neural model as usual and then using its learned feature
representation in classic, interpretable models to perform prediction. Across
seven language models of varying sizes, including four large language models
(LLMs), two datasets at different scales, three classic models, and four
evaluation metrics, we first show that the predictive performance of wrapper
classic models is largely comparable to the original neural models.
  Because classic models are transparent, each model decision is determined by
a known set of training examples that can be directly shown to users. Our
pipeline thus preserves the predictive performance of neural language models
while faithfully attributing classic model decisions to training data. Among
other use cases, such attribution enables model decisions to be contested based
on responsible training instances. Compared to prior work, our approach
achieves higher coverage and correctness in identifying which training data to
remove to change a model decision. To reproduce findings, our source code is
online at: https://github.com/SamSoup/WrapperBox.
