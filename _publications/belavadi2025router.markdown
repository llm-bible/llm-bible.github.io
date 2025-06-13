---
layout: publication
title: 'Routenator: A Router-based Multi-modal Architecture For Generating Synthetic Training Data For Function Calling Llms'
authors: Vibha Belavadi, Tushar Vatsa, Dewang Sultania, Suhas Suresha, Ishita Verma, Cheng Chen, Tracy Holloway King, Michael Friedrich
conference: "https://aclanthology.org/2025.knowledgenlp-1.10/ KnowledgeNLP 2025"
year: 2025
bibkey: belavadi2025router
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.10495'}
tags: ['RAG', 'Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'Applications', 'Reinforcement Learning', 'Pretraining Methods']
---
This paper addresses fine-tuning Large Language Models (LLMs) for function calling tasks when real user interaction data is unavailable. In digital content creation tools, where users express their needs through natural language queries that must be mapped to API calls, the lack of real-world task-specific data and privacy constraints for training on it necessitate synthetic data generation. Existing approaches to synthetic data generation fall short in diversity and complexity, failing to replicate real-world data distributions and leading to suboptimal performance after LLM fine-tuning. We present a novel router-based architecture that leverages domain resources like content metadata and structured knowledge graphs, along with text-to-text and vision-to-text language models to generate high-quality synthetic training data. Our architecture's flexible routing mechanism enables synthetic data generation that matches observed real-world distributions, addressing a fundamental limitation of traditional approaches. Evaluation on a comprehensive set of real user queries demonstrates significant improvements in both function classification accuracy and API parameter selection. Models fine-tuned with our synthetic data consistently outperform traditional approaches, establishing new benchmarks for function calling tasks.
