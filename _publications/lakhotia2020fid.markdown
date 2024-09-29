---
layout: publication
title: Fid45;ex Improving Sequence45;to45;sequence Models For Extractive Rationale Generation
authors: Lakhotia Kushal, Paranjape Bhargavi, Ghoshal Asish, Yih Wen-tau, Mehdad Yashar, Iyer Srinivasan
conference: "Arxiv"
year: 2020
bibkey: lakhotia2020fid
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2012.15482"}
tags: ['Applications', 'Interpretability And Explainability', 'Merging', 'Model Architecture', 'RAG', 'Training Techniques']
---
Natural language (NL) explanations of model predictions are gaining popularity as a means to understand and verify decisions made by large black45;box pre45;trained models for NLP tasks such as Question Answering (QA) and Fact Verification. Recently pre45;trained sequence to sequence (seq2seq) models have proven to be very effective in jointly making predictions as well as generating NL explanations. However these models have many shortcomings; they can fabricate explanations even for incorrect predictions they are difficult to adapt to long input documents and their training requires a large amount of labeled data. In this paper we develop FiD45;Ex which addresses these shortcomings for seq2seq models by 1) introducing sentence markers to eliminate explanation fabrication by encouraging extractive generation 2) using the fusion45;in45;decoder architecture to handle long input contexts and 3) intermediate fine45;tuning on re45;structured open domain QA datasets to improve few45;shot performance. FiD45;Ex significantly improves over prior work in terms of explanation metrics and task accuracy on multiple tasks from the ERASER explainability benchmark both in the fully supervised and in the few45;shot settings.
