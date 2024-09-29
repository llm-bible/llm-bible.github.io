---
layout: publication
title: "Is Crowdsourcing Breaking Your Bank? Cost-effective Fine-tuning Of Pre-trained Language Models With Proximal Policy Optimization"
authors: Yang Shuo, Kasneci Gjergji
conference: "Arxiv"
year: 2024
bibkey: yang2024is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.18284"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Wide usage of ChatGPT has highlighted the potential of reinforcement learning from human feedback. However its training pipeline relies on manual ranking a resource-intensive process. To reduce labor costs we propose a self-supervised text ranking approach for applying Proximal-Policy-Optimization to fine-tune language models while eliminating the need for human annotators. Our method begins with probabilistic sampling to encourage a language model to generate diverse responses for each input. We then employ TextRank and ISODATA algorithms to rank and cluster these responses based on their semantics. Subsequently we construct a reward model to learn the rank and optimize our generative policy. Our experimental results conducted using two language models on three tasks demonstrate that the models trained by our method considerably outperform baselines regarding BLEU GLEU and METEOR scores. Furthermore our manual evaluation shows that our ranking results exhibit a remarkably high consistency with that of humans. This research significantly reduces training costs of proximal policy-guided models and demonstrates the potential for self-correction of language models.
