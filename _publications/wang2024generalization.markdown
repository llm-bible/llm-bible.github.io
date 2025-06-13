---
layout: publication
title: 'Generalization V.s. Memorization: Tracing Language Models'' Capabilities Back To Pretraining Data'
authors: Xinyi Wang, Antonis Antoniades, Yanai Elazar, Alfonso Amayuelas, Alon Albalak, Kexun Zhang, William Yang Wang
conference: "Arxiv"
year: 2024
bibkey: wang2024generalization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.14985"}
tags: ['Pretraining Methods', 'Training Techniques', 'Applications', 'Reinforcement Learning']
---
The impressive capabilities of large language models (LLMs) have sparked
debate over whether these models genuinely generalize to unseen tasks or
predominantly rely on memorizing vast amounts of pretraining data. To explore
this issue, we introduce an extended concept of memorization, distributional
memorization, which measures the correlation between the LLM output
probabilities and the pretraining data frequency. To effectively capture
task-specific pretraining data frequency, we propose a novel task-gram language
model, which is built by counting the co-occurrence of semantically related
\\(n\\)-gram pairs from task inputs and outputs in the pretraining corpus. Using
the Pythia models trained on the Pile dataset, we evaluate four distinct tasks:
machine translation, factual question answering, world knowledge understanding,
and math reasoning. Our findings reveal varying levels of memorization, with
the strongest effect observed in factual question answering. Furthermore, while
model performance improves across all tasks as LLM size increases, only factual
question answering shows an increase in memorization, whereas machine
translation and reasoning tasks exhibit greater generalization, producing more
novel outputs. This study demonstrates that memorization plays a larger role in
simpler, knowledge-intensive tasks, while generalization is the key for harder,
reasoning-based tasks, providing a scalable method for analyzing large
pretraining corpora in greater depth.
