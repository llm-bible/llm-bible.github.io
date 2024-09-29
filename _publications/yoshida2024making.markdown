---
layout: publication
title: Making The Most Of Your Model Methods For Finetuning And Applying Pretrained Transformers
authors: Yoshida Davis
conference: "Arxiv"
year: 2024
bibkey: yoshida2024making
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.16241"}
tags: ['Applications', 'BERT', 'Efficiency And Optimization', 'GPT', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Transformer']
---
This thesis provides methods and analysis of models which make progress on this goal. The techniques outlined are task agnostic and should provide benefit when used with nearly any transformer LM. We introduce two new finetuning methods which add new capabilities to the models they are used on. The first adds a recurrence mechanism which removes the fixed45;window sized constraint and improves the efficiency of a transformer decoder. The second allows masked language models (MLMs) to be used for initialization of both the encoder and decoder of a non45;autoregressive sequence45;to45;sequence transformer opening up generative applications of models which were previously only used for natural language understanding tasks. We also introduce two new techniques for improving the quality of predictions of any transformer decoder without additional finetuning. One hidden state optimization can be applied to any transformer decoder to improve the quality of predictions at inference time especially for few45;shot classification. The other conditional beam search allows practitioners to search for natural language generation (NLG) model outputs with high likelihood while conditioning on the event that the output is not degenerate (e.g. empty repetitive etc.). Finally we provide theoretical and empirical insights on the divergence of model45;likelihood and output quality which has widely been observed in prior work. These insights apply to any model which represents a distribution over text and apply to language models which are not transformers or even autoregressive. We argue that the NLP community has to some extent misunderstood the implications of these findings and encourage a point of view which has more nuance.
