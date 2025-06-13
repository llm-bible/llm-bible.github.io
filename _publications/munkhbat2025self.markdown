---
layout: publication
title: 'Self-training Elicits Concise Reasoning In Large Language Models'
authors: Tergel Munkhbat, Namgyu Ho, Seo Hyun Kim, Yongjin Yang, Yujin Kim, Se-young Yun
conference: "Arxiv"
year: 2025
bibkey: munkhbat2025self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20122"}
  - {name: "Code", url: "https://github.com/TergelMunkhbat/concise-reasoning"}
tags: ['Training Techniques', 'Few-Shot', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Prompting', 'In-Context Learning']
---
Chain-of-thought (CoT) reasoning has enabled large language models (LLMs) to
utilize additional computation through intermediate tokens to solve complex
tasks. However, we posit that typical reasoning traces contain many redundant
tokens, incurring extraneous inference costs. Upon examination of the output
distribution of current LLMs, we find evidence on their latent ability to
reason more concisely, relative to their default behavior. To elicit this
capability, we propose simple fine-tuning methods which leverage self-generated
concise reasoning paths obtained by best-of-N sampling and few-shot
conditioning, in task-specific settings. Our combined method achieves a 30%
reduction in output tokens on average, across five model families on GSM8K and
MATH, while maintaining average accuracy. By exploiting the fundamental
stochasticity and in-context learning capabilities of LLMs, our self-training
approach robustly elicits concise reasoning on a wide range of models,
including those with extensive post-training. Code is available at
https://github.com/TergelMunkhbat/concise-reasoning
