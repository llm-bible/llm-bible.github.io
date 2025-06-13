---
layout: publication
title: 'Intent Detection In The Age Of Llms'
authors: Gaurav Arora, Shreya Jain, Srujana Merugu
conference: "Arxiv"
year: 2024
bibkey: arora2024intent
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.01627'}
tags: ['Transformer', 'Training Techniques', 'Applications', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Intent detection is a critical component of task-oriented dialogue systems
(TODS) which enables the identification of suitable actions to address user
utterances at each dialog turn. Traditional approaches relied on
computationally efficient supervised sentence transformer encoder models, which
require substantial training data and struggle with out-of-scope (OOS)
detection. The emergence of generative large language models (LLMs) with
intrinsic world knowledge presents new opportunities to address these
challenges. In this work, we adapt 7 SOTA LLMs using adaptive in-context
learning and chain-of-thought prompting for intent detection, and compare their
performance with contrastively fine-tuned sentence transformer (SetFit) models
to highlight prediction quality and latency tradeoff. We propose a hybrid
system using uncertainty based routing strategy to combine the two approaches
that along with negative data augmentation results in achieving the best of
both worlds ( i.e. within 2% of native LLM accuracy with 50% less latency). To
better understand LLM OOS detection capabilities, we perform controlled
experiments revealing that this capability is significantly influenced by the
scope of intent labels and the size of the label space. We also introduce a
two-step approach utilizing internal LLM representations, demonstrating
empirical gains in OOS detection accuracy and F1-score by >5% for the
Mistral-7B model.
