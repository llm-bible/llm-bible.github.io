---
layout: publication
title: 'Adversarial Attacks On Llm-as-a-judge Systems: Insights From Prompt Injections'
authors: Narek Maloyan, Dmitry Namiot
conference: "Arxiv"
year: 2025
bibkey: maloyan2025adversarial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.18333"}
tags: ['Tools', 'GPT', 'Model Architecture', 'Security', 'Prompting']
---
LLM as judge systems used to assess text quality code correctness and
argument strength are vulnerable to prompt injection attacks. We introduce a
framework that separates content author attacks from system prompt attacks and
evaluate five models Gemma 3.27B Gemma 3.4B Llama 3.2 3B GPT 4 and Claude 3
Opus on four tasks with various defenses using fifty prompts per condition.
Attacks achieved up to seventy three point eight percent success smaller models
proved more vulnerable and transferability ranged from fifty point five to
sixty two point six percent. Our results contrast with Universal Prompt
Injection and AdvPrompter We recommend multi model committees and comparative
scoring and release all code and datasets
