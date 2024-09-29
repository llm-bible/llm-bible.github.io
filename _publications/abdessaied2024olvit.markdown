---
layout: publication
title: Olvit Multi-modal State Tracking Via Attention-based Embeddings For Video-grounded Dialog
authors: Abdessaied Adnen, Von Hochmeister Manuel, Bulling Andreas
conference: "Arxiv"
year: 2024
bibkey: abdessaied2024olvit
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13146"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
We present the Object Language Video Transformer (OLViT) - a novel model for video dialog operating over a multi-modal attention-based dialog state tracker. Existing video dialog models struggle with questions requiring both spatial and temporal localization within videos long-term temporal reasoning and accurate object tracking across multiple dialog turns. OLViT addresses these challenges by maintaining a global dialog state based on the output of an Object State Tracker (OST) and a Language State Tracker (LST) while the OST attends to the most important objects within the video the LST keeps track of the most important linguistic co-references to previous dialog turns. In stark contrast to previous works our approach is generic by nature and is therefore capable of learning continuous multi-modal dialog state representations of the most relevant objects and rounds. As a result they can be seamlessly integrated into Large Language Models (LLMs) and offer high flexibility in dealing with different datasets and tasks. Evaluations on the challenging DVD (response classification) and SIMMC 2.1 (response generation) datasets show that OLViT achieves new state-of-the-art performance across both datasets.
