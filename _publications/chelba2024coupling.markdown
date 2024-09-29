---
layout: publication
title: Coupling Speech Encoders With Downstream Text Models
authors: Chelba Ciprian, Schalkwyk Johan
conference: "Arxiv"
year: 2024
bibkey: chelba2024coupling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.17605"}
tags: ['Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
We present a modular approach to building cascade speech translation (AST) models that guarantees that the resulting model performs no worse than the 145;best cascade baseline while preserving state45;of45;the45;art speech recognition (ASR) and text translation (MT) performance for a given task. Our novel contribution is the use of an exporter layer that is trained under L245;loss to ensure a strong match between ASR embeddings and the MT token embeddings for the 145;best sequence. The exporter output embeddings are fed directly to the MT model in lieu of 145;best token embeddings thus guaranteeing that the resulting model performs no worse than the 145;best cascade baseline while allowing back45;propagation gradient to flow from the MT model into the ASR components. The matched45;embeddings cascade architecture provide a significant improvement over its 145;best counterpart in scenarios where incremental training of the MT model is not an option and yet we seek to improve quality by leveraging (speech transcription translated transcription) data provided with the AST task. The gain disappears when the MT model is incrementally trained on the parallel text data available with the AST task. The approach holds promise for other scenarios that seek to couple ASR encoders and immutable text models such at large language models (LLM).
