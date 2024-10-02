---
layout: publication
title: 'User-controlled Knowledge Fusion In Large Language Models: Balancing Creativity And Hallucination'
authors: Zhang Chen
conference: "Arxiv"
year: 2023
bibkey: zhang2023user
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.16139"}
tags: ['Applications', 'BERT', 'Fine Tuning', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
In modern dialogue systems, the use of Large Language Models (LLMs) has grown exponentially due to their capacity to generate diverse, relevant, and creative responses. Despite their strengths, striking a balance between the LLMs' creativity and their faithfulness to external knowledge remains a key challenge. This paper presents an innovative user-controllable mechanism that modulates the balance between an LLM's imaginative capabilities and its adherence to factual information. Our approach incorporates a numerical tag during the fine-tuning phase of the LLM's training, representing the degree of faithfulness to the reference knowledge in the generated responses. This degree is computed through an automated process that measures lexical overlap using ROUGE scores, semantic similarity using Sentence-BERT embeddings, and an LLM's self-evaluation score. During model inference, users can manipulate this numerical tag, thus controlling the degree of the LLM's reliance on external knowledge. We conduct extensive experiments across various scenarios, demonstrating the adaptability of our method and its efficacy in ensuring the quality and accuracy of the LLM's responses. The results highlight the potential of our approach to enhance the versatility of LLMs while maintaining a balance between creativity and hallucination.
