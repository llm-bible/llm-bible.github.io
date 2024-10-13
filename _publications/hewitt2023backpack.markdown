---
layout: publication
title: 'Backpack Language Models'
authors: Hewitt John, Thickstun John, Manning Christopher D., Liang Percy
conference: "Arxiv"
year: 2023
bibkey: hewitt2023backpack
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.16765"}
tags: ['Applications', 'Ethics And Bias', 'GPT', 'Interpretability And Explainability', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
We present Backpacks: a new neural architecture that marries strong modeling
performance with an interface for interpretability and control. Backpacks learn
multiple non-contextual sense vectors for each word in a vocabulary, and
represent a word in a sequence as a context-dependent, non-negative linear
combination of sense vectors in this sequence. We find that, after training,
sense vectors specialize, each encoding a different aspect of a word. We can
interpret a sense vector by inspecting its (non-contextual, linear) projection
onto the output space, and intervene on these interpretable hooks to change the
model's behavior in predictable ways. We train a 170M-parameter Backpack
language model on OpenWebText, matching the loss of a GPT-2 small
(124Mparameter) Transformer. On lexical similarity evaluations, we find that
Backpack sense vectors outperform even a 6B-parameter Transformer LM's word
embeddings. Finally, we present simple algorithms that intervene on sense
vectors to perform controllable text generation and debiasing. For example, we
can edit the sense vocabulary to tend more towards a topic, or localize a
source of gender bias to a sense vector and globally suppress that sense.
