---
layout: publication
title: "CROME: Cross-modal Adapters For Efficient Multimodal LLM"
authors: Ebrahimi Sayna, Arik Sercan O., Nama Tejas, Pfister Tomas
conference: "Arxiv"
year: 2024
bibkey: ebrahimi2024cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.06610"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Multimodal Models', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Multimodal Large Language Models (MLLMs) demonstrate remarkable image-language capabilities but their widespread use faces challenges in cost-effective training and adaptation. Existing approaches often necessitate expensive language model retraining and limited adaptability. Additionally the current focus on zero-shot performance improvements offers insufficient guidance for task-specific tuning. We propose CROME an efficient vision-language instruction tuning framework. It features a novel gated cross-modal adapter that effectively combines visual and textual representations prior to input into a frozen LLM. This lightweight adapter trained with minimal parameters enables efficient cross-modal understanding. Notably CROME demonstrates superior zero-shot performance on standard visual question answering and instruction-following benchmarks. Moreover it yields fine-tuning with exceptional parameter efficiency competing with task-specific specialist state-of-the-art methods. CROME demonstrates the potential of pre-LM alignment for building scalable adaptable and parameter-efficient multimodal models.
