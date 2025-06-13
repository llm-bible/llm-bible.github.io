---
layout: publication
title: 'LLM Braces: Straightening Out LLM Predictions With Relevant Sub-updates'
authors: Ying Shen, Lifu Huang
conference: "Arxiv"
year: 2025
bibkey: shen2025llm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.16334'}
tags: ['Language Modeling', 'Transformer', 'RAG', 'Applications', 'Model Architecture', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Recent findings reveal that much of the knowledge in a Transformer-based
Large Language Model (LLM) is encoded in its feed-forward (FFN) layers, where
each FNN layer can be interpreted as the summation of sub-updates, each
corresponding to a weighted column vector from the FFN's value parameter matrix
that often encodes human-interpretable concepts. In light of this, we
hypothesize that model performance and behaviors can be further enhanced and
controlled by modulating the contributions of these sub-updates based on their
relevance to the input or target output style, and propose LLMBRACES, a novel
and efficient method that computes relevance scores associated with value
vectors in FFN layers and leverages these scores to dynamically adjust the
contribution of sub-updates. By optimizing sub-update contributions, LLMBRACES
refines the prediction process, leading to more accurate and reliable outputs,
much like a 'brace' providing support and stability. Moreover, LLMBRACES can be
extended to support conditional control over generation characteristics, such
as sentiment, thereby offering fine-grained steering of LLM outputs. Extensive
experiments on various LLMs-including Qwen2.5-1.5B, Llama2-7B, and
Llama3-8B-demonstrate that LLMBRACES outperforms baseline approaches in both
fine-tuning and zero-shot settings while requiring significantly fewer tunable
parameters, up to 75% fewer compared to LoRA. Furthermore, LLMBRACES excels in
sentiment-controlled generation and toxicity reduction, highlighting its
potential for flexible, controlled text generation across applications.
