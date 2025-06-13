---
layout: publication
title: 'Do Encoder Representations Of Generative Dialogue Models Encode Sufficient Information About The Task ?'
authors: Prasanna Parthasarathi, Joelle Pineau, Sarath Chandar
conference: "Arxiv"
year: 2021
bibkey: parthasarathi2021do
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2106.10622'}
tags: ['Language Modeling', 'Transformer', 'Applications', 'Model Architecture', 'Pretraining Methods']
---
Predicting the next utterance in dialogue is contingent on encoding of users'
input text to generate appropriate and relevant response in data-driven
approaches. Although the semantic and syntactic quality of the language
generated is evaluated, more often than not, the encoded representation of
input is not evaluated. As the representation of the encoder is essential for
predicting the appropriate response, evaluation of encoder representation is a
challenging yet important problem. In this work, we showcase evaluating the
text generated through human or automatic metrics is not sufficient to
appropriately evaluate soundness of the language understanding of dialogue
models and, to that end, propose a set of probe tasks to evaluate encoder
representation of different language encoders commonly used in dialogue models.
From experiments, we observe that some of the probe tasks are easier and some
are harder for even sophisticated model architectures to learn. And, through
experiments we observe that RNN based architectures have lower performance on
automatic metrics on text generation than transformer model but perform better
than the transformer model on the probe tasks indicating that RNNs might
preserve task information better than the Transformers.
