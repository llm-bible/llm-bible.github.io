---
layout: publication
title: 'Knowledge Graph Large Language Model (KG-LLM) For Link Prediction'
authors: Shu Dong, Chen Tianle, Jin Mingyu, Zhang Chong, Du Mengnan, Zhang Yongfeng
conference: "Arxiv"
year: 2024
bibkey: shu2024knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.07311"}
tags: ['Applications', 'Prompting', 'RAG', 'Tools']
---
The task of multi-hop link prediction within knowledge graphs (KGs) stands as a challenge in the field of knowledge graph analysis, as it requires the model to reason through and understand all intermediate connections before making a prediction. In this paper, we introduce the Knowledge Graph Large Language Model (KG-LLM), a novel framework that leverages large language models (LLMs) for knowledge graph tasks. We first convert structured knowledge graph data into natural language and then use these natural language prompts to fine-tune LLMs to enhance multi-hop link prediction in KGs. By converting the KG to natural language prompts, our framework is designed to learn the latent representations of entities and their interrelations. To show the efficacy of the KG-LLM Framework, we fine-tune three leading LLMs within this framework, including Flan-T5, LLaMa2 and Gemma. Further, we explore the framework's potential to provide LLMs with zero-shot capabilities for handling previously unseen prompts. Experimental results show that KG-LLM significantly improves the models' generalization capabilities, leading to more accurate predictions in unfamiliar scenarios.
