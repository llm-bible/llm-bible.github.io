---
layout: publication
title: Scaling Laws For Forgetting When Fine45;tuning Large Language Models
authors: Kalajdzievski Damjan
conference: "Arxiv"
year: 2024
bibkey: kalajdzievski2024scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.05605"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Large Scale Training', 'Model Architecture', 'Reinforcement Learning', 'Responsible AI', 'Scaling Laws']
---
We study and quantify the problem of forgetting when fine45;tuning pre45;trained large language models (LLMs) on a downstream task. We find that parameter45;efficient fine45;tuning (PEFT) strategies such as Low45;Rank Adapters (LoRA) still suffer from catastrophic forgetting. In particular we identify a strong inverse linear relationship between the fine45;tuning performance and the amount of forgetting when fine45;tuning LLMs with LoRA. We further obtain precise scaling laws that show forgetting increases as a shifted power law in the number of parameters fine45;tuned and the number of update steps. We also examine the impact of forgetting on knowledge reasoning and the safety guardrails trained into Llama 2 7B chat. Our study suggests that forgetting cannot be avoided through early stopping or by varying the number of parameters fine45;tuned. We believe this opens up an important safety45;critical direction for future research to evaluate and develop fine45;tuning schemes which mitigate forgetting
