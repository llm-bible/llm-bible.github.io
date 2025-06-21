---
layout: publication
title: 'Visbert: Hidden-state Visualizations For Transformers'
authors: "Betty Van Aken, Benjamin Winter, Alexander L\xF6ser, Felix A. Gers"
conference: Companion Proceedings of the Web Conference 2020
year: 2020
citations: 18
bibkey: vanaken2020hidden
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2011.04507'}]
tags: [Transformer, Interpretability and Explainability, BERT]
---
Explainability and interpretability are two important concepts, the absence
of which can and should impede the application of well-performing neural
networks to real-world problems. At the same time, they are difficult to
incorporate into the large, black-box models that achieve state-of-the-art
results in a multitude of NLP tasks. Bidirectional Encoder Representations from
Transformers (BERT) is one such black-box model. It has become a staple
architecture to solve many different NLP tasks and has inspired a number of
related Transformer models. Understanding how these models draw conclusions is
crucial for both their improvement and application. We contribute to this
challenge by presenting VisBERT, a tool for visualizing the contextual token
representations within BERT for the task of (multi-hop) Question Answering.
Instead of analyzing attention weights, we focus on the hidden states resulting
from each encoder block within the BERT model. This way we can observe how the
semantic representations are transformed throughout the layers of the model.
VisBERT enables users to get insights about the model's internal state and to
explore its inference steps or potential shortcomings. The tool allows us to
identify distinct phases in BERT's transformations that are similar to a
traditional NLP pipeline and offer insights during failed predictions.