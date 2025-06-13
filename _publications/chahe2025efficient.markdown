---
layout: publication
title: 'Reasondrive: Efficient Visual Question Answering For Autonomous Vehicles With Reasoning-enhanced Small Vision-language Models'
authors: Amirhosein Chahe, Lifeng Zhou
conference: "Arxiv"
year: 2025
bibkey: chahe2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.10757"}
tags: ['Fine-Tuning', 'Responsible AI', 'GPT', 'Applications', 'Model Architecture', 'Language Modeling', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models', 'Prompting']
---
Vision-language models (VLMs) show promise for autonomous driving but often
lack transparent reasoning capabilities that are critical for safety. We
investigate whether explicitly modeling reasoning during fine-tuning enhances
VLM performance on driving decision tasks. Using GPT-4o, we generate structured
reasoning chains for driving scenarios from the DriveLM benchmark with
category-specific prompting strategies. We compare reasoning-based fine-tuning,
answer-only fine-tuning, and baseline instruction-tuned models across multiple
small VLM families (Llama 3.2, Llava 1.5, and Qwen 2.5VL). Our results
demonstrate that reasoning-based fine-tuning consistently outperforms
alternatives, with Llama3.2-11B-reason achieving the highest performance.
Models fine-tuned with reasoning show substantial improvements in accuracy and
text generation quality, suggesting explicit reasoning enhances internal
representations for driving decisions. These findings highlight the importance
of transparent decision processes in safety-critical domains and offer a
promising direction for developing more interpretable autonomous driving
systems.
