---
layout: publication
title: 'The Effect Of Fine-tuning On Language Model Toxicity'
authors: Will Hawkins, Brent Mittelstadt, Chris Russell
conference: "Arxiv"
year: 2024
bibkey: hawkins2024effect
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.15821'}
tags: ['Security', 'Training Techniques', 'Fine-Tuning', 'Responsible AI', 'Pretraining Methods']
---
Fine-tuning language models has become increasingly popular following the
proliferation of open models and improvements in cost-effective parameter
efficient fine-tuning. However, fine-tuning can influence model properties such
as safety. We assess how fine-tuning can impact different open models'
propensity to output toxic content. We assess the impacts of fine-tuning Gemma,
Llama, and Phi models on toxicity through three experiments. We compare how
toxicity is reduced by model developers during instruction-tuning. We show that
small amounts of parameter-efficient fine-tuning on developer-tuned models via
low-rank adaptation on a non-adversarial dataset can significantly alter these
results across models. Finally, we highlight the impact of this in the wild,
demonstrating how toxicity rates of models fine-tuned by community contributors
can deviate in hard-to-predict ways.
