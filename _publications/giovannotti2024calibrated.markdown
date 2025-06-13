---
layout: publication
title: 'Calibrated Large Language Models For Binary Question Answering'
authors: Patrizio Giovannotti, Alexander Gammerman
conference: "Arxiv"
year: 2024
bibkey: giovannotti2024calibrated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01122"}
tags: ['Applications', 'Interpretability and Explainability']
---
Quantifying the uncertainty of predictions made by large language models
(LLMs) in binary text classification tasks remains a challenge. Calibration, in
the context of LLMs, refers to the alignment between the model's predicted
probabilities and the actual correctness of its predictions. A well-calibrated
model should produce probabilities that accurately reflect the likelihood of
its predictions being correct. We propose a novel approach that utilizes the
inductive Venn--Abers predictor (IVAP) to calibrate the probabilities
associated with the output tokens corresponding to the binary labels. Our
experiments on the BoolQ dataset using the Llama 2 model demonstrate that IVAP
consistently outperforms the commonly used temperature scaling method for
various label token choices, achieving well-calibrated probabilities while
maintaining high predictive quality. Our findings contribute to the
understanding of calibration techniques for LLMs and provide a practical
solution for obtaining reliable uncertainty estimates in binary question
answering tasks, enhancing the interpretability and trustworthiness of LLM
predictions.
