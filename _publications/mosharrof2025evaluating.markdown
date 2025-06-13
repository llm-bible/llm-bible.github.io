---
layout: publication
title: 'Evaluating And Enhancing Out-of-domain Generalization Of Task-oriented Dialog Systems For Task Completion Without Turn-level Dialog Annotations'
authors: Adib Mosharrof, Moghis Fereidouni, A. B. Siddique
conference: "Arxiv"
year: 2025
bibkey: mosharrof2025evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13310"}
tags: ['Fine-Tuning', 'Tools', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Traditional task-oriented dialog (ToD) systems rely heavily on
labor-intensive turn-level annotations, such as dialogue states and policy
labels, for training. This work explores whether large language models (LLMs)
can be fine-tuned solely on natural language dialogs to perform ToD tasks,
without requiring such annotations. We evaluate their ability to generalize to
unseen domains and compare their performance with models trained on fully
annotated data. Through extensive experiments with three open-source LLMs of
varying sizes and two diverse ToD datasets, we find that models fine-tuned
without turn-level annotations generate coherent and contextually appropriate
responses. However, their task completion performance - measured by accurate
execution of API calls - remains suboptimal, with the best models achieving
only around 53% success in unseen domains. To improve task completion, we
propose ZeroToD, a framework that incorporates a schema augmentation mechanism
to enhance API call accuracy and overall task completion rates, particularly in
out-of-domain settings. We also compare ZeroToD with fine-tuning-free
alternatives, such as prompting off-the-shelf LLMs, and find that our framework
enables smaller, fine-tuned models that outperform large-scale proprietary LLMs
in task completion. Additionally, a human study evaluating informativeness,
fluency, and task completion confirms our empirical findings. These findings
suggest the feasibility of developing cost-effective, scalable, and zero-shot
generalizable ToD systems for real-world applications.
