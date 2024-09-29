---
layout: publication
title: Chop Chop BERT: Visual Question Answering By Chopping Visualbert's Heads
authors: Gao Chenyu, Zhu Qi, Wang Peng, Wu Qi
conference: "Arxiv"
year: 2021
bibkey: gao2021chop
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2104.14741"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Vision-and-Language (VL) pre-training has shown great potential on many related downstream tasks such as Visual Question Answering (VQA) one of the most popular problems in the VL field. All of these pre-trained models (such as VisualBERT ViLBERT LXMERT and UNITER) are built with Transformer which extends the classical attention mechanism to multiple layers and heads. To investigate why and how these models work on VQA so well in this paper we explore the roles of individual heads and layers in Transformer models when handling 12 different types of questions. Specifically we manually remove (chop) heads (or layers) from a pre-trained VisualBERT model at a time and test it on different levels of questions to record its performance. As shown in the interesting echelon shape of the result matrices experiments reveal different heads and layers are responsible for different question types with higher-level layers activated by higher-level visual reasoning questions. Based on this observation we design a dynamic chopping module that can automatically remove heads and layers of the VisualBERT at an instance level when dealing with different questions. Our dynamic chopping module can effectively reduce the parameters of the original model by 5037; while only damaging the accuracy by less than 137; on the VQA task.
