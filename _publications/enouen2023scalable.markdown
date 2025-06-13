---
layout: publication
title: 'Textgenshap: Scalable Post-hoc Explanations In Text Generation With Long Documents'
authors: James Enouen, Hootan Nakhost, Sayna Ebrahimi, Sercan O Arik, Yan Liu, Tomas Pfister
conference: "Arxiv"
year: 2023
bibkey: enouen2023scalable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.01279'}
tags: ['Language Modeling', 'Interpretability and Explainability', 'GPT', 'Applications', 'Reinforcement Learning', 'Interpretability', 'Pretraining Methods']
---
Large language models (LLMs) have attracted huge interest in practical
applications given their increasingly accurate responses and coherent reasoning
abilities. Given their nature as black-boxes using complex reasoning processes
on their inputs, it is inevitable that the demand for scalable and faithful
explanations for LLMs' generated content will continue to grow. There have been
major developments in the explainability of neural network models over the past
decade. Among them, post-hoc explainability methods, especially Shapley values,
have proven effective for interpreting deep learning models. However, there are
major challenges in scaling up Shapley values for LLMs, particularly when
dealing with long input contexts containing thousands of tokens and
autoregressively generated output sequences. Furthermore, it is often unclear
how to effectively utilize generated explanations to improve the performance of
LLMs. In this paper, we introduce TextGenSHAP, an efficient post-hoc
explanation method incorporating LM-specific techniques. We demonstrate that
this leads to significant increases in speed compared to conventional Shapley
value computations, reducing processing times from hours to minutes for
token-level explanations, and to just seconds for document-level explanations.
In addition, we demonstrate how real-time Shapley values can be utilized in two
important scenarios, providing better understanding of long-document question
answering by localizing important words and sentences; and improving existing
document retrieval systems through enhancing the accuracy of selected passages
and ultimately the final responses.
