---
layout: publication
title: 'Optimizing Llms For Italian: Reducing Token Fertility And Enhancing Efficiency Through Vocabulary Adaptation'
authors: Luca Moroni, Giovanni Puccetti, Pere-lluis Huguet Cabot, Andrei Stefan Bejgu, Edoardo Barba, Alessio Miaschi, Felice Dell'orletta, Andrea Esuli, Roberto Navigli
conference: "Arxiv"
year: 2025
bibkey: moroni2025optimizing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.17025'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'Pretraining Methods']
---
The number of pretrained Large Language Models (LLMs) is increasing steadily,
though the majority are designed predominantly for the English language. While
state-of-the-art LLMs can handle other languages, due to language contamination
or some degree of multilingual pretraining data, they are not optimized for
non-English languages, leading to inefficient encoding (high token "fertility")
and slower inference speed. In this work, we thoroughly compare a variety of
vocabulary adaptation techniques for optimizing English LLMs for the Italian
language, and put forward Semantic Alignment Vocabulary Adaptation (SAVA), a
novel method that leverages neural mapping for vocabulary substitution. SAVA
achieves competitive performance across multiple downstream tasks, enhancing
grounded alignment strategies. We adapt two LLMs: Mistral-7b-v0.1, reducing
token fertility by 25%, and Llama-3.1-8B, optimizing the vocabulary and
reducing the number of parameters by 1 billion. We show that, following the
adaptation of the vocabulary, these models can recover their performance with a
relatively limited stage of continual training on the target language. Finally,
we test the capabilities of the adapted models on various multi-choice and
generative tasks.
