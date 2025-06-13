---
layout: publication
title: 'Generalizing Large Language Model Usability Across Resource-constrained'
authors: Yun-da Tsai
conference: "Arxiv"
year: 2025
bibkey: tsai2025generalizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17040"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'Applications', 'RAG', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models', 'Prompting']
---
Large Language Models (LLMs) have achieved remarkable success across a wide range of natural language tasks, and recent efforts have sought to extend their capabilities to multimodal domains and resource-constrained environments. However, existing approaches often rely on costly supervised fine-tuning or assume fixed training conditions, limiting their generalization when facing unseen modalities, limited data, or restricted compute resources. This dissertation presents a systematic study toward generalizing LLM usability under real-world constraints. First, it introduces a robust text-centric alignment framework that enables LLMs to seamlessly integrate diverse modalities-including text, images, tables, and any modalities - via natural language interfaces. This approach supports in-context adaptation to unseen or dynamically changing modalities without requiring retraining. To enhance robustness against noisy and missing modalities, an adversarial prompting technique is proposed, generating semantically challenging perturbations at the prompt level to stress-test model reliability. Beyond multimodal setting, the dissertation investigates inference-time optimization strategies for LLMs, leveraging prompt search and uncertainty quantification to improve performance without additional model training. This perspective offers an efficient alternative to scaling model parameters or retraining from scratch. Additionally, the work addresses low-resource domains such as Verilog code generation by designing correct-by-construction synthetic data pipelines and logic-enhanced reasoning models, achieving state-of-the-art performance with minimal data. Together, these contributions form a unified effort to enhance the adaptability, scalability, and efficiency of large language models under practical constraints.
