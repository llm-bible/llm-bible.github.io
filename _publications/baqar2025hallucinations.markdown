---
layout: publication
title: 'Hallucinations And Truth: A Comprehensive Accuracy Evaluation Of RAG, Lora And Dora'
authors: Mohammad Baqar, Rajat Khanda
conference: "Arxiv"
year: 2025
bibkey: baqar2025hallucinations
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.10497'}
tags: ['RAG', 'Efficiency and Optimization', 'Applications', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Recent advancements in Generative AI have significantly improved the
efficiency and adaptability of natural language processing (NLP) systems,
particularly through Retrieval-Augmented Generation (RAG), Low-Rank Adaptation
(LoRA), and Weight-Decomposed Low-Rank Adaptation (DoRA). RAG integrates
external knowledge to enhance factual consistency in generative outputs, while
LoRA enables parameter-efficient fine-tuning of large language models (LLMs).
DoRA further refines this process by optimizing fine-tuning through adaptive
parameter ranking and domain-aware weight adjustments, improving learning
efficiency while maintaining inference performance.
  This paper presents a large-scale empirical evaluation of RAG, LoRA, and
DoRA, with model fine-tuning and generation performance assessed on 20,000
FAQ-based queries, while the knowledge base spans 400,000 entries. The study
analyzes key performance metrics such as accuracy, relevance, and inference
latency. Experimental results demonstrate that DoRA achieves the highest
accuracy (90.1%), relevance score (0.88), and lowest latency (110 ms per
query), outperforming both LoRA and RAG in real-world, domain-specific
generative AI applications.
  Furthermore, this study examines the trade-offs between fine-tuning
efficiency, computational cost, and real-time adaptability across different
models. Findings highlight RAG's effectiveness in knowledge grounding, LoRA's
cost-efficient domain adaptation, and DoRA's ability to balance fine-tuning
efficiency with model precision. These insights provide practical guidance for
deploying AI-driven generative systems in accuracy-critical domains such as
healthcare, finance, and legal services, ensuring scalability, reliability, and
optimal performance in dynamic environments.
