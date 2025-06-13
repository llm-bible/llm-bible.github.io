---
layout: publication
title: 'Safeguard Fine-tuned Llms Through Pre- And Post-tuning Model Merging'
authors: Hua Farn, Hsuan Su, Shachi H Kumar, Saurav Sahay, Shang-tse Chen, Hung-yi Lee
conference: "Arxiv"
year: 2024
bibkey: farn2024safeguard
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.19512"}
tags: ['Responsible AI', 'Training Techniques', 'Merging', 'Pretraining Methods', 'Fine-Tuning']
---
Fine-tuning large language models (LLMs) for downstream tasks is a widely
adopted approach, but it often leads to safety degradation in safety-aligned
LLMs. Currently, many solutions address this issue by incorporating additional
safety data, which can be impractical in many cases. In this paper, we address
the question: How can we improve downstream task performance while preserving
safety in LLMs without relying on additional safety data? We propose a simple
and effective method that maintains the inherent safety of LLMs while enhancing
their downstream task performance: merging the weights of pre- and
post-fine-tuned safety-aligned models. Experimental results across various
downstream tasks, models, and merging methods demonstrate that this approach
effectively mitigates safety degradation while improving downstream task
performance, offering a practical solution for adapting safety-aligned LLMs.
