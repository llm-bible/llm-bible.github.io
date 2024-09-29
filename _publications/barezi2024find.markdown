---
layout: publication
title: "Find The Gap: Knowledge Base Reasoning For Visual Question Answering"
authors: Barezi Elham J., Kordjamshidi Parisa
conference: "Arxiv"
year: 2024
bibkey: barezi2024find
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10226"}
tags: ['Applications', 'Model Architecture', 'RAG', 'Training Techniques']
---
We analyze knowledge-based visual question answering for which given a question the models need to ground it into the visual modality and retrieve the relevant knowledge from a given large knowledge base (KB) to be able to answer. Our analysis has two folds one based on designing neural architectures and training them from scratch and another based on large pre-trained language models (LLMs). Our research questions are 1) Can we effectively augment models by explicit supervised retrieval of the relevant KB information to solve the KB-VQA problem 2) How do task-specific and LLM-based models perform in the integration of visual and external knowledge and multi-hop reasoning over both sources of information 3) Is the implicit knowledge of LLMs sufficient for KB-VQA and to what extent it can replace the explicit KB Our results demonstrate the positive impact of empowering task-specific and LLM models with supervised external and visual knowledge retrieval models. Our findings show that though LLMs are stronger in 1-hop reasoning they suffer in 2-hop reasoning in comparison with our fine-tuned NN model even if the relevant information from both modalities is available to the model. Moreover we observed that LLM models outperform the NN model for KB-related questions which confirms the effectiveness of implicit knowledge in LLMs however they do not alleviate the need for external KB.
