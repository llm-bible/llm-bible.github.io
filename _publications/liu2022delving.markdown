---
layout: publication
title: 'Delving Deeper Into Cross-lingual Visual Question Answering'
authors: Liu Chen, Pfeiffer Jonas, Korhonen Anna, Vulić Ivan, Gurevych Iryna
conference: "Arxiv"
year: 2022
bibkey: liu2022delving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2202.07630"}
tags: ['Applications', 'Ethics And Bias', 'Fine Tuning', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Visual question answering (VQA) is one of the crucial vision-and-language tasks. Yet existing VQA research has mostly focused on the English language due to a lack of suitable evaluation resources. Previous work on cross-lingual VQA has reported poor zero-shot transfer performance of current multilingual multimodal Transformers with large gaps to monolingual performance without any deeper analysis. In this work we delve deeper into the different aspects of cross-lingual VQA aiming to understand the impact of 1) modeling methods and choices including architecture inductive bias fine-tuning; 2) learning biases including question types and modality biases in cross-lingual setups. The key results of our analysis are 1) We show that simple modifications to the standard training setup can substantially reduce the transfer gap to monolingual English performance yielding +10 accuracy points over existing methods. 2) We analyze cross-lingual VQA across different question types of varying complexity for different multilingual multimodal Transformers and identify question types that are the most difficult to improve on. 3) We provide an analysis of modality biases present in training data and models revealing why zero-shot performance gaps remain for certain question types and languages.
