---
layout: publication
title: 'Osiris: A Lightweight Open-source Hallucination Detection System'
authors: Alex Shan, John Bauer, Christopher D. Manning
conference: "Arxiv"
year: 2025
bibkey: shan2025lightweight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.04844"}
tags: ['Fine-Tuning', 'GPT', 'Survey Paper', 'RAG', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
Retrieval-Augmented Generation (RAG) systems have gained widespread adoption
by application builders because they leverage sources of truth to enable Large
Language Models (LLMs) to generate more factually sound responses. However,
hallucinations, instances of LLM responses that are unfaithful to the provided
context, often prevent these systems from being deployed in production
environments. Current hallucination detection methods typically involve human
evaluation or the use of closed-source models to review RAG system outputs for
hallucinations. Both human evaluators and closed-source models suffer from
scaling issues due to their high costs and slow inference speeds. In this work,
we introduce a perturbed multi-hop QA dataset with induced hallucinations. Via
supervised fine-tuning on our dataset, we achieve better recall with a 7B model
than GPT-4o on the RAGTruth hallucination detection benchmark and offer
competitive performance on precision and accuracy, all while using a fraction
of the parameters. Code is released at our repository.
