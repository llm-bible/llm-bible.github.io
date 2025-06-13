---
layout: publication
title: 'Steerconf: Steering Llms For Confidence Elicitation'
authors: Ziang Zhou, Tianyuan Jin, Jieming Shi, Qing Li
conference: "Arxiv"
year: 2025
bibkey: zhou2025steering
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.02863'}
tags: ['RAG', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Tools', 'Fine-Tuning', 'Training Techniques', 'GPT', 'Quantization', 'Prompting', 'Reinforcement Learning', 'Ethics and Bias', 'Responsible AI', 'Pretraining Methods']
---
Large Language Models (LLMs) exhibit impressive performance across diverse domains but often suffer from overconfidence, limiting their reliability in critical applications. We propose SteerConf, a novel framework that systematically steers LLMs' confidence scores to improve their calibration and reliability. SteerConf introduces three key components: (1) a steering prompt strategy that guides LLMs to produce confidence scores in specified directions (e.g., conservative or optimistic) by leveraging prompts with varying steering levels; (2) a steered confidence consistency measure that quantifies alignment across multiple steered confidences to enhance calibration; and (3) a steered confidence calibration method that aggregates confidence scores using consistency measures and applies linear quantization for answer selection. SteerConf operates without additional training or fine-tuning, making it broadly applicable to existing LLMs. Experiments on seven benchmarks spanning professional knowledge, common sense, ethics, and reasoning tasks, using advanced LLM models (GPT-3.5, LLaMA 3, GPT-4), demonstrate that SteerConf significantly outperforms existing methods, often by a significant margin. Our findings highlight the potential of steering the confidence of LLMs to enhance their reliability for safer deployment in real-world applications.
