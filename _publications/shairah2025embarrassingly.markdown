---
layout: publication
title: 'An Embarrassingly Simple Defense Against LLM Abliteration Attacks'
authors: Harethah Abu Shairah, Hasan Abed Al Kader Hammoud, Bernard Ghanem, George Turkiyyah
conference: "Arxiv"
year: 2025
bibkey: shairah2025embarrassingly
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.19056'}
tags: ['Security', 'Training Techniques', 'Prompting', 'Fine-Tuning', 'Responsible AI', 'Pretraining Methods']
---
Large language models (LLMs) are typically aligned to comply with safety guidelines by refusing harmful instructions. A recent attack, termed abliteration, isolates and suppresses the single latent direction most responsible for refusal behavior, enabling the model to generate unethical content. We propose a defense that modifies how models generate refusals. We construct an extended-refusal dataset that contains harmful prompts with a full response that justifies the reason for refusal. We then fine-tune Llama-2-7B-Chat and Qwen2.5-Instruct (1.5B and 3B parameters) on our extended-refusal dataset, and evaluate the resulting systems on a set of harmful prompts. In our experiments, extended-refusal models maintain high refusal rates, dropping at most by 10%, whereas baseline models' refusal rates drop by 70-80% after abliteration. A broad evaluation of safety and utility shows that extended-refusal fine-tuning neutralizes the abliteration attack while preserving general performance.
