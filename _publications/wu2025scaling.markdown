---
layout: publication
title: 'Scaling Context, Not Parameters: Training A Compact 7B Language Model For Efficient Long-context Processing'
authors: Chen Wu, Yin Song
conference: "Arxiv"
year: 2025
bibkey: wu2025scaling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.08651'}
tags: ['RAG', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'In-Context Learning', 'Pretraining Methods']
---
We present MegaBeam-Mistral-7B, a language model that supports 512K-token context length. Our work addresses practical limitations in long-context training, supporting real-world tasks such as compliance monitoring and verification. Evaluated on three long-context benchmarks, our 7B-parameter model demonstrates superior in-context learning performance on HELMET and robust retrieval and tracing capability on RULER. It is currently the only open model to achieve competitive long-range reasoning on BABILong at 512K context length without RAG or targeted fine-tuning. Released as fully open source under the Apache 2.0 license, the model has been downloaded over 100,000 times on Hugging Face. Model available at: https://huggingface.co/aws-prototyping/MegaBeam-Mistral-7B-512k
