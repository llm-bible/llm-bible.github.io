---
layout: publication
title: 'Stabilizing Reasoning In Medical Llms With Continued Pretraining And Reasoning Preference Optimization'
authors: Wataru Kawakami, Keita Suzuki, Junichiro Iwasawa
conference: "Arxiv"
year: 2025
bibkey: kawakami2025stabilizing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.18080'}
tags: ['Interpretability and Explainability', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Model Architecture', 'Fine-Tuning', 'GPT', 'Prompting', 'Pretraining Methods']
---
Large Language Models (LLMs) show potential in medicine, yet clinical
adoption is hindered by concerns over factual accuracy, language-specific
limitations (e.g., Japanese), and critically, their reliability when required
to generate reasoning explanations -- a prerequisite for trust. This paper
introduces Preferred-MedLLM-Qwen-72B, a 72B-parameter model optimized for the
Japanese medical domain to achieve both high accuracy and stable reasoning. We
employ a two-stage fine-tuning process on the Qwen2.5-72B base model: first,
Continued Pretraining (CPT) on a comprehensive Japanese medical corpus instills
deep domain knowledge. Second, Reasoning Preference Optimization (RPO), a
preference-based method, enhances the generation of reliable reasoning pathways
while preserving high answer accuracy. Evaluations on the Japanese Medical
Licensing Exam benchmark (IgakuQA) show Preferred-MedLLM-Qwen-72B achieves
state-of-the-art performance (0.868 accuracy), surpassing strong proprietary
models like GPT-4o (0.866). Crucially, unlike baseline or CPT-only models which
exhibit significant accuracy degradation (up to 11.5% and 3.8% respectively
on IgakuQA) when prompted for explanations, our model maintains its high
accuracy (0.868) under such conditions. This highlights RPO's effectiveness in
stabilizing reasoning generation. This work underscores the importance of
optimizing for reliable explanations alongside accuracy. We release the
Preferred-MedLLM-Qwen-72B model weights to foster research into trustworthy
LLMs for specialized, high-stakes applications.
