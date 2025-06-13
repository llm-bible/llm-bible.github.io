---
layout: publication
title: 'Preemptive Hallucination Reduction: An Input-level Approach For Multimodal Language Model'
authors: Nokimul Hasan Arif, Shadman Rabby, Md Hefzul Hossain Papon, Sabbir Ahmed
conference: "Arxiv"
year: 2025
bibkey: arif2025preemptive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.24007'}
tags: ['GPT', 'Tools', 'Training Techniques', 'Fine-Tuning', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Visual hallucinations in Large Language Models (LLMs), where the model generates responses that are inconsistent with the visual input, pose a significant challenge to their reliability, particularly in contexts where precise and trustworthy outputs are critical. Current research largely emphasizes post-hoc correction or model-specific fine-tuning strategies, with limited exploration of preprocessing techniques to address hallucination issues at the input stage. This study presents a novel ensemble-based preprocessing framework that adaptively selects the most appropriate filtering approach -- noise reduced (NR), edge enhanced (EE), or unaltered input (org) based on the type of question posed, resulting into reduced hallucination without requiring any modifications to the underlying model architecture or training pipeline. Evaluated on the `HaloQuest' dataset -- a benchmark designed to test multimodal reasoning on visually complex inputs, our method achieves a 44.3% reduction in hallucination rates, as measured by Natural Language Inference (NLI) scores using SelfCheckGPT. This demonstrates that intelligent input conditioning alone can significantly enhance factual grounding in LLM responses. The findings highlight the importance of adaptive preprocessing techniques in mitigating hallucinations, paving the way for more reliable multimodal systems capable of addressing real-world challenges.
