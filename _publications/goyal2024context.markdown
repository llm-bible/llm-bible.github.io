---
layout: publication
title: 'Context-parametric Inversion: Why Instruction Finetuning Can Worsen Context Reliance'
authors: Sachin Goyal, Christina Baek, J. Zico Kolter, Aditi Raghunathan
conference: "Arxiv"
year: 2024
bibkey: goyal2024context
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10796"}
tags: ['Pretraining Methods', 'Training Techniques', 'Reinforcement Learning']
---
A standard practice when using large language models is for users to
supplement their instruction with an input context containing new information
for the model to process. However, models struggle to reliably follow the input
context, especially when it conflicts with their parametric knowledge from
pretraining. In-principle, one would expect models to adapt to the user context
better after instruction finetuning, particularly when handling knowledge
conflicts. However, we observe a surprising failure mode: during instruction
tuning, the context reliance under knowledge conflicts initially increases as
expected, but then gradually decreases as instruction finetuning progresses.
This happens while the performance on standard benchmarks keeps on increasing
far after this drop. We call this phenomenon context-parametric inversion and
observe it across multiple general purpose instruction tuning datasets such as
TULU, Alpaca and Ultrachat, across different model families like Llama,
Mistral, and Pythia. We perform various controlled studies and theoretical
analysis to show that context-parametric inversion occurs due to examples in
the instruction finetuning data where the input context provides information
that aligns with model's parametric knowledge. Our analysis suggests some
natural mitigation strategies with limited but insightful gains, and serves as
a useful starting point in addressing this deficiency in instruction
finetuning.
