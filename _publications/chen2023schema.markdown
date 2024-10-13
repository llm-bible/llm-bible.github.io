---
layout: publication
title: 'Schema-guided Semantic Accuracy: Faithfulness In Task-oriented Dialogue Response Generation'
authors: Chen Jinghong, Lin Weizhe, Byrne Bill
conference: "Arxiv"
year: 2023
bibkey: chen2023schema
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.12568"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Ensuring that generated utterances are faithful to dialogue actions is
crucial for Task-Oriented Dialogue Response Generation. Slot Error Rate (SER)
only partially measures generation quality in that it solely assesses
utterances generated from non-categorical slots whose values are expected to be
reproduced exactly. Utterances generated from categorical slots, which are more
variable, are not assessed by SER. We propose Schema-Guided Semantic Accuracy
(SGSAcc) to evaluate utterances generated from both categorical and
non-categorical slots by recognizing textual entailment. We show that SGSAcc
can be applied to evaluate utterances generated from a wide range of dialogue
actions in the Schema Guided Dialogue (SGD) dataset with good agreement with
human judgment. We also identify a previously overlooked weakness in generating
faithful utterances from categorical slots in unseen domains. We show that
prefix tuning applied to T5 generation can address this problem. We further
build an ensemble of prefix-tuning and fine-tuning models that achieves the
lowest SER reported and high SGSAcc on the SGD dataset.
