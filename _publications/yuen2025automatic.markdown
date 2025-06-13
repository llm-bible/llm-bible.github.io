---
layout: publication
title: 'Automatic Dataset Generation For Knowledge Intensive Question Answering Tasks'
authors: Sizhe Yuen, Ting Su, Ziyang Wang, Yali Du, Adam J. Sobey
conference: "Arxiv"
year: 2025
bibkey: yuen2025automatic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.14212'}
tags: ['RAG', 'Training Techniques', 'BERT', 'Model Architecture', 'Fine-Tuning', 'Applications', 'Pretraining Methods']
---
A question-answering (QA) system is to search suitable answers within a knowledge base. Current QA systems struggle with queries requiring complex reasoning or real-time knowledge integration. They are often supplemented with retrieval techniques on a data source such as Retrieval-Augmented Generation (RAG). However, RAG continues to face challenges in handling complex reasoning and logical connections between multiple sources of information. A novel approach for enhancing Large Language Models (LLMs) in knowledge-intensive QA tasks is presented through the automated generation of context-based QA pairs. This methodology leverages LLMs to create fine-tuning data, reducing reliance on human labelling and improving model comprehension and reasoning capabilities. The proposed system includes an automated QA generator and a model fine-tuner, evaluated using perplexity, ROUGE, BLEU, and BERTScore. Comprehensive experiments demonstrate improvements in logical coherence and factual accuracy, with implications for developing adaptable Artificial Intelligence (AI) systems. Mistral-7b-v0.3 outperforms Llama-3-8b with BERT F1, BLEU, and ROUGE scores 0.858, 0.172, and 0.260 of for the LLM generated QA pairs compared to scores of 0.836, 0.083, and 0.139 for the human annotated QA pairs.
