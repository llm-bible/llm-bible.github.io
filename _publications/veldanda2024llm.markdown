---
layout: publication
title: 'LLM Surgery: Efficient Knowledge Unlearning And Editing In Large Language Models'
authors: Akshaj Kumar Veldanda, Shi-xiong Zhang, Anirban Das, Supriyo Chakraborty, Stephen Rawls, Sambit Sahu, Milind Naphade
conference: "Arxiv"
year: 2024
bibkey: veldanda2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.13054"}
tags: ['Pretraining Methods', 'Training Techniques', 'Tools']
---
Large language models (LLMs) have revolutionized various domains, yet their
utility comes with significant challenges related to outdated or problematic
knowledge embedded during pretraining. This paper addresses the challenge of
modifying LLMs to unlearn problematic and outdated information while
efficiently integrating new knowledge without retraining from scratch. Here, we
propose LLM Surgery, a framework to efficiently modify LLM behaviour by
optimizing a three component objective function that: (1) Performs reverse
gradient on unlearning dataset (problematic and outdated information), (2)
Performs gradient descent on the update dataset (new and updated information),
and (3) Minimizes the KL divergence on the retain dataset (small subset of
unchanged text), ensuring alignment between pretrained and modified model
outputs. Due to the lack of publicly available datasets specifically tailored
for our novel task, we compiled a new dataset and an evaluation benchmark.
Using Llama2-7B, we demonstrate that LLM Surgery can achieve significant
forgetting on the unlearn set, a 20% increase in accuracy on the update set,
and maintain performance on the retain set.
