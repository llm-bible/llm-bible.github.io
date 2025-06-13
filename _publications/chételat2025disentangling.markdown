---
layout: publication
title: 'Innerthoughts: Disentangling Representations And Predictions In Large Language Models'
authors: Didier Chételat, Joseph Cotnareanu, Rylee Thompson, Yingxue Zhang, Mark Coates
conference: "Arxiv"
year: 2025
bibkey: chételat2025disentangling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.17994'}
tags: ['Transformer', 'Training Techniques', 'Model Architecture', 'Tools', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Large language models (LLMs) contain substantial factual knowledge which is
commonly elicited by multiple-choice question-answering prompts. Internally,
such models process the prompt through multiple transformer layers, building
varying representations of the problem within its hidden states. Ultimately,
however, only the hidden state corresponding to the final layer and token
position are used to predict the answer label. In this work, we propose instead
to learn a small separate neural network predictor module on a collection of
training questions, that take the hidden states from all the layers at the last
temporal position as input and outputs predictions. In effect, such a framework
disentangles the representational abilities of LLMs from their predictive
abilities. On a collection of hard benchmarks, our method achieves considerable
improvements in performance, sometimes comparable to supervised fine-tuning
procedures, but at a fraction of the computational cost.
