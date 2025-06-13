---
layout: publication
title: 'Promptoptme: Error-aware Prompt Compression For Llm-based MT Evaluation Metrics'
authors: Daniil Larionov, Steffen Eger
conference: "Arxiv"
year: 2024
bibkey: larionov2024error
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.16120'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'GPT', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Evaluating the quality of machine-generated natural language content is a
challenging task in Natural Language Processing (NLP). Recently, large language
models (LLMs) like GPT-4 have been employed for this purpose, but they are
computationally expensive due to the extensive token usage required by complex
evaluation prompts. In this paper, we propose a prompt optimization approach
that uses a smaller, fine-tuned language model to compress input data for
evaluation prompt, thus reducing token usage and computational cost when using
larger LLMs for downstream evaluation. Our method involves a two-stage
fine-tuning process: supervised fine-tuning followed by preference optimization
to refine the model's outputs based on human preferences. We focus on Machine
Translation (MT) evaluation and utilize the GEMBA-MQM metric as a starting
point. Our results show a \\(2.37\times\\) reduction in token usage without any
loss in evaluation quality. This work makes state-of-the-art LLM-based metrics
like GEMBA-MQM more cost-effective and efficient, enhancing their accessibility
for broader use.
