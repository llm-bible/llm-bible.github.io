---
layout: publication
title: 'Fine-tuning Large Language Models For Entity Matching'
authors: Steiner Aaron, Peeters Ralph, Bizer Christian
conference: "Arxiv"
year: 2024
bibkey: steiner2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.08185"}
tags: ['Fine Tuning', 'GPT', 'In Context Learning', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Generative large language models (LLMs) are a promising alternative to pre-trained language models for entity matching due to their high zero-shot performance and their ability to generalize to unseen entities. Existing research on using LLMs for entity matching has focused on prompt engineering and in-context learning. This paper explores the potential of fine-tuning LLMs for entity matching. We analyze fine-tuning along two dimensions 1) The representation of training examples where we experiment with adding different types of LLM-generated explanations to the training set and 2) the selection and generation of training examples using LLMs. In addition to the matching performance on the source dataset we investigate how fine-tuning affects the models ability to generalize to other in-domain datasets as well as across topical domains. Our experiments show that fine-tuning significantly improves the performance of the smaller models while the results for the larger models are mixed. Fine-tuning also improves the generalization to in-domain datasets while hurting cross-domain transfer. We show that adding structured explanations to the training set has a positive impact on the performance of three out of four LLMs while the proposed example selection and generation methods only improve the performance of Llama 3.1 8B while decreasing the performance of GPT-4o Mini.
