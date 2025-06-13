---
layout: publication
title: 'Turning Up The Heat: Min-p Sampling For Creative And Coherent LLM Outputs'
authors: Minh Nhat Nguyen, Andrew Baker, Clement Neo, Allen Roush, Andreas Kirsch, Ravid Shwartz-ziv
conference: "In Proceedings of the 2025 International Conference on Learning Representations (ICLR) 2025"
year: 2024
bibkey: nguyen2024turning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01082"}
tags: ['Transformer', 'Tools', 'Applications', 'Language Modeling', 'Model Architecture', 'Pretraining Methods']
---
Large Language Models (LLMs) generate text by sampling the next token from a probability distribution over the vocabulary at each decoding step. Popular sampling methods like top-p (nucleus sampling) often struggle to balance quality and diversity, especially at higher temperatures which lead to incoherent or repetitive outputs. We propose min-p sampling, a dynamic truncation method that adjusts the sampling threshold based on the model's confidence by using the top token's probability as a scaling factor. Our experiments on benchmarks including GPQA, GSM8K, and AlpacaEval Creative Writing show that min-p sampling improves both the quality and diversity of generated text across different model families (Mistral and Llama 3) and model sizes (1B to 123B parameters), especially at higher temperatures. Human evaluations further show a clear preference for min-p sampling, in both text quality and creativity. Min-p sampling has been adopted by popular open-source LLM frameworks, including Hugging Face Transformers, VLLM, and many others, highlighting its considerable impact on improving text generation quality.
