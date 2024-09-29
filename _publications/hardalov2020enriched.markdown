---
layout: publication
title: "Enriched Pre-trained Transformers For Joint Slot Filling And Intent Detection"
authors: Hardalov Momchil, Koychev Ivan, Nakov Preslav
conference: "Arxiv"
year: 2020
bibkey: hardalov2020enriched
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.14848"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Detecting the users intent and finding the corresponding slots among the utterances words are important tasks in natural language understanding. Their interconnected nature makes their joint modeling a standard part of training such models. Moreover data scarceness and specialized vocabularies pose additional challenges. Recently the advances in pre-trained language models namely contextualized models such as ELMo and BERT have revolutionized the field by tapping the potential of training very large models with just a few steps of fine-tuning on a task-specific dataset. Here we leverage such models namely BERT and RoBERTa and we design a novel architecture on top of them. Moreover we propose an intent pooling attention mechanism and we reinforce the slot filling task by fusing intent distributions word features and token representations. The experimental results on standard datasets show that our model outperforms both the current non-BERT state of the art as well as some stronger BERT-based baselines.
