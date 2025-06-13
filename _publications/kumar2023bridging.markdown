---
layout: publication
title: 'Bridging The Language Gap: Dynamic Learning Strategies For Improving Multilingual Performance In Llms'
authors: Somnath Kumar, Vaibhav Balloli, Mercy Ranjit, Kabir Ahuja, Sunayana Sitaram, Kalika Bali, Tanuja Ganu, Akshay Nambi
conference: "COLING 2025"
year: 2023
bibkey: kumar2023bridging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.17740'}
tags: ['RAG', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Large language models (LLMs) have revolutionized various domains but still
struggle with non-Latin scripts and low-resource languages. This paper
addresses the critical challenge of improving multilingual performance without
extensive fine-tuning. We introduce a novel dynamic learning approach that
optimizes prompt strategy, embedding model, and LLM per query at runtime. By
adapting configurations dynamically, our method achieves significant
improvements over static, best and random baselines. It operates efficiently in
both offline and online settings, generalizing seamlessly across new languages
and datasets. Leveraging Retrieval-Augmented Generation (RAG) with
state-of-the-art multilingual embeddings, we achieve superior task performance
across diverse linguistic contexts. Through systematic investigation and
evaluation across 18 diverse languages using popular question-answering (QA)
datasets we show our approach results in 10-15% improvements in multilingual
performance over pre-trained models and 4x gains compared to fine-tuned,
language-specific models.
