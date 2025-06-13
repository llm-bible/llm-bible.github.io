---
layout: publication
title: 'Resource-aware Arabic LLM Creation: Model Adaptation, Integration, And Multi-domain Testing'
authors: Prakash Aryan
conference: "Arxiv"
year: 2024
bibkey: aryan2024resource
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.17548"}
tags: ['Security', 'Training Techniques', 'Efficiency and Optimization', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
This paper presents a novel approach to fine-tuning the Qwen2-1.5B model for
Arabic language processing using Quantized Low-Rank Adaptation (QLoRA) on a
system with only 4GB VRAM. We detail the process of adapting this large
language model to the Arabic domain, using diverse datasets including Bactrian,
OpenAssistant, and Wikipedia Arabic corpora. Our methodology involves custom
data preprocessing, model configuration, and training optimization techniques
such as gradient accumulation and mixed-precision training. We address specific
challenges in Arabic NLP, including morphological complexity, dialectal
variations, and diacritical mark handling. Experimental results over 10,000
training steps show significant performance improvements, with the final loss
converging to 0.1083. We provide comprehensive analysis of GPU memory usage,
training dynamics, and model evaluation across various Arabic language tasks,
including text classification, question answering, and dialect identification.
The fine-tuned model demonstrates robustness to input perturbations and
improved handling of Arabic-specific linguistic phenomena. This research
contributes to multilingual AI by demonstrating a resource-efficient approach
for creating specialized language models, potentially democratizing access to
advanced NLP technologies for diverse linguistic communities. Our work paves
the way for future research in low-resource language adaptation and efficient
fine-tuning of large language models.
