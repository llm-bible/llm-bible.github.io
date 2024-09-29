---
layout: publication
title: "Scaling Laws For Forgetting When Fine-tuning Large Language Models"
authors: Kalajdzievski Damjan
conference: "Arxiv"
year: 2024
bibkey: kalajdzievski2024scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.05605"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Large Scale Training', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Responsible AI', 'Scaling Laws', 'Training Techniques']
---
We study and quantify the problem of forgetting when fine-tuning pre-trained large language models (LLMs) on a downstream task. We find that parameter-efficient fine-tuning (PEFT) strategies such as Low-Rank Adapters (LoRA) still suffer from catastrophic forgetting. In particular we identify a strong inverse linear relationship between the fine-tuning performance and the amount of forgetting when fine-tuning LLMs with LoRA. We further obtain precise scaling laws that show forgetting increases as a shifted power law in the number of parameters fine-tuned and the number of update steps. We also examine the impact of forgetting on knowledge reasoning and the safety guardrails trained into Llama 2 7B chat. Our study suggests that forgetting cannot be avoided through early stopping or by varying the number of parameters fine-tuned. We believe this opens up an important safety-critical direction for future research to evaluate and develop fine-tuning schemes which mitigate forgetting
