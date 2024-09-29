---
layout: publication
title: Soft Prompting For Unlearning In Large Language Models
authors: Bhaila Karuna, Van Minh-hao, Wu Xintao
conference: "Arxiv"
year: 2024
bibkey: bhaila2024soft
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12038"}
  - {name: "Code", url: "https://github.com/karuna-bhaila/llm_unlearning"}
tags: ['Applications', 'Fine Tuning', 'Has Code', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Tools', 'Training Techniques']
---
The widespread popularity of Large Language Models (LLMs) partly due to their unique ability to perform in-context learning has also brought to light the importance of ethical and safety considerations when deploying these pre-trained models. In this work we focus on investigating machine unlearning for LLMs motivated by data protection regulations. In contrast to the growing literature on fine-tuning methods to achieve unlearning we focus on a comparatively lightweight alternative called soft prompting to realize the unlearning of a subset of training data. With losses designed to enforce forgetting as well as utility preservation our framework (textbfS)oft (textbfP)rompting for (textbfU)n(textbfl)earning (SPUL) learns prompt tokens that can be appended to an arbitrary query to induce unlearning of specific examples at inference time without updating LLM parameters. We conduct a rigorous evaluation of the proposed method and our results indicate that SPUL can significantly improve the trade-off between utility and forgetting in the context of text classification and question answering with LLMs. We further validate our method using multiple LLMs to highlight the scalability of our framework and provide detailed insights into the choice of hyperparameters and the influence of the size of unlearning data. Our implementation is available at (url)https://github.com/karuna-bhaila/llm\_unlearning\}.
