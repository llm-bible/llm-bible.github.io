---
layout: publication
title: 'Empowering Smaller Models: Tuning Llama And Gemma With Chain-of-thought For Ukrainian Exam Tasks'
authors: Mykyta Syromiatnikov, Victoria Ruvinskaya, Nataliia Komleva
conference: "Arxiv"
year: 2025
bibkey: syromiatnikov2025empowering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.13988"}
  - {name: "Code", url: "https://github.com/NLPForUA/ZNO"}
tags: ['Fine-Tuning', 'GPT', 'Interpretability and Explainability', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Security', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Leading large language models have demonstrated impressive capabilities in
reasoning-intensive tasks, such as standardized educational testing. However,
they often require extensive training in low-resource settings with
inaccessible infrastructure. Small or compact models, though more efficient,
frequently lack sufficient support for underrepresented languages, leaving a
performance gap in critical domains. This work explores the potential of
parameter-efficient fine-tuning of compact open-weight language models to
handle reasoning-intensive tasks in the underrepresented Ukrainian language,
building on the findings of the ZNO-Eval benchmark. Parameter-efficient
fine-tuning of LLaMA 3.1 (8 billion parameters), LLaMA 3.2 (3 billion
parameters), and Gemma 2 (9 billion parameters) models on chain-of-thought
solutions resulted in a modest test score improvement of up to 17.4% on complex
matching tasks and 1.6% overall compared to tuning on answer letters alone,
offering enhanced interpretability and robustness. In addition, the proposed
tuning method with joint task topic and step-by-step solution generation
outperforms standard chain-of-thought tuning in matching tasks and provides a
5.4% gain over the best LLaMA 3.2 model due to guiding the model to recall and
apply domain-relevant information. Contrasting obtained results with zero-shot
evaluations of leading open-weight and proprietary models such as Qwen,
DeepSeek R1, OpenAI o1 and o3, Gemini, and Claude, highlight that fine-tuning
LLaMA and Gemma models with 2,032 step-by-step solutions and 20 to 50 million
trainable parameters on a single A100 GPU lets them outperform GPT-4o mini,
Mistral Large, and larger open-weight models. This research also evaluates how
merging the quantized adapter with the base model influences the generation
quality. Source code and tuned models are available at
https://github.com/NLPForUA/ZNO.
