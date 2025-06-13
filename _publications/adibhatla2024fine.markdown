---
layout: publication
title: 'Fine-grained Contract NER Using Instruction Based Model'
authors: Hiranmai Sri Adibhatla, Pavan Baswani, Manish Shrivastava
conference: "Arxiv"
year: 2024
bibkey: adibhatla2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.13545"}
tags: ['Training Techniques', 'Few-Shot', 'Language Modeling', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
Lately, instruction-based techniques have made significant strides in
improving performance in few-shot learning scenarios. They achieve this by
bridging the gap between pre-trained language models and fine-tuning for
specific downstream tasks. Despite these advancements, the performance of Large
Language Models (LLMs) in information extraction tasks like Named Entity
Recognition (NER), using prompts or instructions, still falls short of
supervised baselines. The reason for this performance gap can be attributed to
the fundamental disparity between NER and LLMs. NER is inherently a sequence
labeling task, where the model must assign entity-type labels to individual
tokens within a sentence. In contrast, LLMs are designed as a text generation
task. This distinction between semantic labeling and text generation leads to
subpar performance. In this paper, we transform the NER task into a
text-generation task that can be readily adapted by LLMs. This involves
enhancing source sentences with task-specific instructions and answer choices,
allowing for the identification of entities and their types within natural
language. We harness the strength of LLMs by integrating supervised learning
within them. The goal of this combined strategy is to boost the performance of
LLMs in extraction tasks like NER while simultaneously addressing hallucination
issues often observed in LLM-generated content. A novel corpus Contract NER
comprising seven frequently observed contract categories, encompassing named
entities associated with 18 distinct legal entity types is released along with
our baseline models. Our models and dataset are available to the community for
future research * .
