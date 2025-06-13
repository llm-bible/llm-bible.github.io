---
layout: publication
title: 'From Text To Emoji: How Peft-driven Personality Manipulation Unleashes The Emoji Potential In Llms'
authors: Navya Jain, Zekun Wu, Cristian Munoz, Airlie Hilliard, Xin Guan, Adriano Koshiyama, Emre Kazim, Philip Treleaven
conference: "Findings paper of NAACL 2025 and NeurIPS 2024 Workshop on Behavioral Machine Learning"
year: 2024
bibkey: jain2024from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.10245"}
tags: ['Training Techniques', 'Pretraining Methods', 'Interpretability', 'Fine-Tuning', 'Interpretability and Explainability', 'Prompting', 'In-Context Learning']
---
The manipulation of the personality traits of large language models (LLMs)
has emerged as a key area of research. Methods like prompt-based In-Context
Knowledge Editing (IKE) and gradient-based Model Editor Networks (MEND) have
been explored but show irregularity and variability; IKE depends on the prompt,
leading to variability and sensitivity, while MEND yields inconsistent and
gibberish outputs. To address this, we employed Opinion QA Based
Parameter-Efficient Fine-Tuning (PEFT), specifically Quantized Low-Rank
Adaptation (QLoRA), to manipulate the Big Five personality traits: Openness,
Conscientiousness, Extraversion, Agreeableness, and Neuroticism. After PEFT,
models such as Mistral-7B-Instruct and LLaMA-2-7B-chat showed a latent
behaviour by generating emojis for certain traits, despite no emojis being
present in the PEFT data. For instance, LLaMA-2-7B-chat generated emojis in
99.5% of extraversion-related test instances, while Mistral-7B-Instruct did so
in 92.5% of openness-related test instances. ICL Explainability analysis
indicated that the LLMs used emojis intentionally to express these traits.
Mechanistic Interpretability analysis showed that this latent behaviour of LLMs
could be traced to specific neurons that became activated or amplified after
PEFT. This paper provides a number of novel contributions. First, introducing
an Opinion QA dataset for PEFT-driven personality manipulation; second,
developing metric models to benchmark LLM personality traits; third,
demonstrating PEFT's superiority over IKE in personality manipulation; and
finally, analysing and validating emoji usage through explainability methods
such as Mechanistic Interpretability and In-context learning Explainability
methods.
