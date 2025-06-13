---
layout: publication
title: 'A Llama Walks Into The ''bar'': Efficient Supervised Fine-tuning For Legal Reasoning In The Multi-state Bar Exam'
authors: Rean Fernandes, André Biedenkapp, Frank Hutter, Noor Awad
conference: "Arxiv"
year: 2025
bibkey: fernandes2025llama
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.04945'}
tags: ['Interpretability and Explainability', 'Few-Shot', 'Training Techniques', 'GPT', 'Model Architecture', 'Fine-Tuning', 'Prompting', 'Applications', 'Ethics and Bias', 'Pretraining Methods']
---
Legal reasoning tasks present unique challenges for large language models
(LLMs) due to the complexity of domain-specific knowledge and reasoning
processes. This paper investigates how effectively smaller language models
(Llama 2 7B and Llama 3 8B) can be fine-tuned with a limited dataset of 1,514
Multi-state Bar Examination (MBE) questions to improve legal question answering
accuracy. We evaluate these models on the 2022 MBE questions licensed from JD
Advising, the same dataset used in the 'GPT-4 passes the Bar exam' study. Our
methodology involves collecting approximately 200 questions per legal domain
across 7 domains. We distill the dataset using Llama 3 (70B) to transform
explanations into a structured IRAC (Issue, Rule, Application, Conclusion)
format as a guided reasoning process to see if it results in better performance
over the non-distilled dataset. We compare the non-fine-tuned models against
their supervised fine-tuned (SFT) counterparts, trained for different sample
sizes per domain, to study the effect on accuracy and prompt adherence. We also
analyse option selection biases and their mitigation following SFT. In
addition, we consolidate the performance across multiple variables: prompt type
(few-shot vs zero-shot), answer ordering (chosen-option first vs
generated-explanation first), response format (Numbered list vs Markdown vs
JSON), and different decoding temperatures. Our findings show that
domain-specific SFT helps some model configurations achieve close to human
baseline performance, despite limited computational resources and a relatively
small dataset. We release both the gathered SFT dataset and the family of
Supervised Fine-tuned (SFT) adapters optimised for MBE performance. This
establishes a practical lower bound on resources needed towards achieving
effective legal question answering in smaller LLMs.
