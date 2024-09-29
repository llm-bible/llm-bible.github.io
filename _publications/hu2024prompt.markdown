---
layout: publication
title: Prompt Perturbation In Retrieval45;augmented Generation Based Large Language Models
authors: Hu Zhibo Hye-young, Wang Chen Hye-young, Shu Yanfeng Hye-young, Helen Hye-young, Paik, Zhu Liming
conference: "Arxiv"
year: 2024
bibkey: hu2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.07179"}
tags: ['Applications', 'Efficiency And Optimization', 'Language Modeling', 'Prompting', 'RAG', 'Security', 'Tools']
---
The robustness of large language models (LLMs) becomes increasingly important as their use rapidly grows in a wide range of domains. Retrieval45;Augmented Generation (RAG) is considered as a means to improve the trustworthiness of text generation from LLMs. However how the outputs from RAG45;based LLMs are affected by slightly different inputs is not well studied. In this work we find that the insertion of even a short prefix to the prompt leads to the generation of outputs far away from factually correct answers. We systematically evaluate the effect of such prefixes on RAG by introducing a novel optimization technique called Gradient Guided Prompt Perturbation (GGPP). GGPP achieves a high success rate in steering outputs of RAG45;based LLMs to targeted wrong answers. It can also cope with instructions in the prompts requesting to ignore irrelevant context. We also exploit LLMs neuron activation difference between prompts with and without GGPP perturbations to give a method that improves the robustness of RAG45;based LLMs through a highly effective detector trained on neuron activation triggered by GGPP generated prompts. Our evaluation on open45;sourced LLMs demonstrates the effectiveness of our methods.
