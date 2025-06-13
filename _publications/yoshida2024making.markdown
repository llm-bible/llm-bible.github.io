---
layout: publication
title: 'Making The Most Of Your Model: Methods For Finetuning And Applying Pretrained Transformers'
authors: Davis Yoshida
conference: "Arxiv"
year: 2024
bibkey: yoshida2024making
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.16241"}
tags: ['Masked Language Model', 'Efficiency and Optimization', 'Model Architecture', 'Few-Shot', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'BERT', 'Transformer', 'Applications']
---
This thesis provides methods and analysis of models which make progress on
this goal. The techniques outlined are task agnostic, and should provide
benefit when used with nearly any transformer LM. We introduce two new
finetuning methods which add new capabilities to the models they are used on.
The first adds a recurrence mechanism, which removes the fixed-window sized
constraint and improves the efficiency of a transformer decoder. The second
allows masked language models (MLMs) to be used for initialization of both the
encoder and decoder of a non-autoregressive sequence-to-sequence transformer,
opening up generative applications of models which were previously only used
for natural language understanding tasks.
  We also introduce two new techniques for improving the quality of predictions
of any transformer decoder without additional finetuning. One, hidden state
optimization, can be applied to any transformer decoder to improve the quality
of predictions at inference time, especially for few-shot classification. The
other, conditional beam search, allows practitioners to search for natural
language generation (NLG) model outputs with high likelihood while conditioning
on the event that the output is not degenerate (e.g. empty, repetitive, etc.).
  Finally, we provide theoretical and empirical insights on the divergence of
model-likelihood and output quality which has widely been observed in prior
work. These insights apply to any model which represents a distribution over
text, and apply to language models which are not transformers or even
autoregressive. We argue that the NLP community has, to some extent,
misunderstood the implications of these findings, and encourage a point of view
which has more nuance.
