---
layout: publication
title: Fid-ex\: Improving Sequence-to-sequence Models For Extractive Rationale Generation
authors: Lakhotia Kushal, Paranjape Bhargavi, Ghoshal Asish, Yih Wen-tau, Mehdad Yashar, Iyer Srinivasan
conference: "Arxiv"
year: 2020
bibkey: lakhotia2020fid
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2012.15482"}
tags: ['Applications', 'Few Shot', 'Fine Tuning', 'Interpretability And Explainability', 'Merging', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Natural language (NL) explanations of model predictions are gaining popularity as a means to understand and verify decisions made by large black-box pre-trained models for NLP tasks such as Question Answering (QA) and Fact Verification. Recently pre-trained sequence to sequence (seq2seq) models have proven to be very effective in jointly making predictions as well as generating NL explanations. However these models have many shortcomings; they can fabricate explanations even for incorrect predictions they are difficult to adapt to long input documents and their training requires a large amount of labeled data. In this paper we develop FiD-Ex which addresses these shortcomings for seq2seq models by 1) introducing sentence markers to eliminate explanation fabrication by encouraging extractive generation 2) using the fusion-in-decoder architecture to handle long input contexts and 3) intermediate fine-tuning on re-structured open domain QA datasets to improve few-shot performance. FiD-Ex significantly improves over prior work in terms of explanation metrics and task accuracy on multiple tasks from the ERASER explainability benchmark both in the fully supervised and in the few-shot settings.
