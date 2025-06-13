---
layout: publication
title: 'Facilitating NSFW Text Detection In Open-domain Dialogue Systems Via Knowledge Distillation'
authors: Huachuan Qiu, Shuai Zhang, Hongliang He, Anqi Li, Zhenzhong Lan
conference: "Arxiv"
year: 2023
bibkey: qiu2023facilitating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.09749'}
tags: ['RAG', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'BERT', 'Model Architecture', 'GPT', 'Applications', 'Responsible AI']
---
NSFW (Not Safe for Work) content, in the context of a dialogue, can have
severe side effects on users in open-domain dialogue systems. However, research
on detecting NSFW language, especially sexually explicit content, within a
dialogue context has significantly lagged behind. To address this issue, we
introduce CensorChat, a dialogue monitoring dataset aimed at NSFW dialogue
detection. Leveraging knowledge distillation techniques involving GPT-4 and
ChatGPT, this dataset offers a cost-effective means of constructing NSFW
content detectors. The process entails collecting real-life human-machine
interaction data and breaking it down into single utterances and single-turn
dialogues, with the chatbot delivering the final utterance. ChatGPT is employed
to annotate unlabeled data, serving as a training set. Rationale validation and
test sets are constructed using ChatGPT and GPT-4 as annotators, with a
self-criticism strategy for resolving discrepancies in labeling. A BERT model
is fine-tuned as a text classifier on pseudo-labeled data, and its performance
is assessed. The study emphasizes the importance of AI systems prioritizing
user safety and well-being in digital conversations while respecting freedom of
expression. The proposed approach not only advances NSFW content detection but
also aligns with evolving user protection needs in AI-driven dialogues.
