---
layout: publication
title: 'Improving Consistency In Large Language Models Through Chain Of Guidance'
authors: Harsh Raj, Vipul Gupta, Domenic Rosati, Subhabrata Majumdar
conference: "Arxiv"
year: 2025
bibkey: raj2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15924"}
tags: ['Fine-Tuning', 'Applications', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Consistency is a fundamental dimension of trustworthiness in Large Language
Models (LLMs). For humans to be able to trust LLM-based applications, their
outputs should be consistent when prompted with inputs that carry the same
meaning or intent. Despite this need, there is no known mechanism to control
and guide LLMs to be more consistent at inference time. In this paper, we
introduce a novel alignment strategy to maximize semantic consistency in LLM
outputs. Our proposal is based on Chain of Guidance (CoG), a multistep
prompting technique that generates highly consistent outputs from LLMs. For
closed-book question-answering (Q&A) tasks, when compared to direct prompting,
the outputs generated using CoG show improved consistency. While other
approaches like template-based responses and majority voting may offer
alternative paths to consistency, our work focuses on exploring the potential
of guided prompting. We use synthetic data sets comprised of consistent
input-output pairs to fine-tune LLMs to produce consistent and correct outputs.
Our fine-tuned models are more than twice as consistent compared to base models
and show strong generalization capabilities by producing consistent outputs
over datasets not used in the fine-tuning process.
