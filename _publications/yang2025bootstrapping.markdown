---
layout: publication
title: 'Bootstrapping LLM Robustness For VLM Safety Via Reducing The Pretraining Modality Gap'
authors: Wenhan Yang, Spencer Stice, Ali Payani, Baharan Mirzasoleiman
conference: "Arxiv"
year: 2025
bibkey: yang2025bootstrapping
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.24208'}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'GPT', 'Fine-Tuning', 'Prompting', 'Multimodal Models', 'Responsible AI', 'Pretraining Methods']
---
Ensuring Vision-Language Models (VLMs) generate safe outputs is crucial for their reliable deployment. However, LVLMs suffer from drastic safety degradation compared to their LLM backbone. Even blank or irrelevant images can trigger LVLMs to generate harmful responses to prompts that would otherwise be refused in text-only contexts. The modality gap between image and text representations has been recently hypothesized to contribute to safety degradation of LVLMs. However, if and how the amount of modality gap affects LVLMs' safety is not studied. In this work, we show that the amount of modality gap is highly inversely correlated with VLMs' safety. Then, we show that this modality gap is introduced during pretraining LVLMs and persists through fine-tuning. Inspired by this observation, we propose a regularization to reduce the modality gap during pretraining. Our extensive experiments on LLaVA v1.5, ShareGPT4V, and MiniGPT-4 show that our method substantially improves safety alignment of LVLMs, reducing unsafe rate by up to 16.3% without compromising performance, and can further boost existing defenses by up to 18.2%.
