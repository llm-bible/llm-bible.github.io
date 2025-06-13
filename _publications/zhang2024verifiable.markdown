---
layout: publication
title: 'Vtune: Verifiable Fine-tuning For Llms Through Backdooring'
authors: Eva Zhang, Arka Pal, Akilesh Potti, Micah Goldblum
conference: "Arxiv"
year: 2024
bibkey: zhang2024verifiable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.06611"}
tags: ['Fine-Tuning', 'Ethics and Bias', 'Interpretability', 'Security', 'Training Techniques', 'Pretraining Methods']
---
As fine-tuning large language models (LLMs) becomes increasingly prevalent,
users often rely on third-party services with limited visibility into their
fine-tuning processes. This lack of transparency raises the question: how do
consumers verify that fine-tuning services are performed correctly? For
instance, a service provider could claim to fine-tune a model for each user,
yet simply send all users back the same base model. To address this issue, we
propose vTune, a simple method that uses a small number of backdoor data points
added to the training data to provide a statistical test for verifying that a
provider fine-tuned a custom model on a particular user's dataset. Unlike
existing works, vTune is able to scale to verification of fine-tuning on
state-of-the-art LLMs, and can be used both with open-source and closed-source
models. We test our approach across several model families and sizes as well as
across multiple instruction-tuning datasets, and find that the statistical test
is satisfied with p-values on the order of \\(\sim 10^\{-40\}\\), with no negative
impact on downstream task performance. Further, we explore several attacks that
attempt to subvert vTune and demonstrate the method's robustness to these
attacks.
