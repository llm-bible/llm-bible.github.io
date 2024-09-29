---
layout: publication
title: Text Encoders Lack Knowledge&#58; Leveraging Generative Llms For Domain-specific Semantic Textual Similarity
authors: Gatto Joseph, Sharif Omar, Seegmiller Parker, Bohlman Philip, Preum Sarah Masud
conference: "Arxiv"
year: 2023
bibkey: gatto2023text
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.06541"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Amidst the sharp rise in the evaluation of large language models (LLMs) on various tasks we find that semantic textual similarity (STS) has been under-explored. In this study we show that STS can be cast as a text generation problem while maintaining strong performance on multiple STS benchmarks. Additionally we show generative LLMs significantly outperform existing encoder-based STS models when characterizing the semantic similarity between two texts with complex semantic relationships dependent on world knowledge. We validate this claim by evaluating both generative LLMs and existing encoder-based STS models on three newly collected STS challenge sets which require world knowledge in the domains of Health Politics and Sports. All newly collected data is sourced from social media content posted after May 2023 to ensure the performance of closed-source models like ChatGPT cannot be credited to memorization. Our results show that on average generative LLMs outperform the best encoder-only baselines by an average of 22.337; on STS tasks requiring world knowledge. Our results suggest generative language models with STS-specific prompting strategies achieve state-of-the-art performance in complex domain-specific STS tasks.
