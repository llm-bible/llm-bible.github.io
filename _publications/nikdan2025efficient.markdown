---
layout: publication
title: 'Efficient Data Selection At Scale Via Influence Distillation'
authors: Mahdi Nikdan, Vincent Cohen-addad, Dan Alistarh, Vahab Mirrokni
conference: "Arxiv"
year: 2025
bibkey: nikdan2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.19051"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Distillation', 'Pretraining Methods', 'Fine-Tuning']
---
Effective data selection is critical for efficient training of modern Large Language Models (LLMs). This paper introduces Influence Distillation, a novel, mathematically-justified framework for data selection that employs second-order information to optimally weight training samples. By distilling each sample's influence on a target distribution, our method assigns model-specific weights that are used to select training data for LLM fine-tuning, guiding it toward strong performance on the target domain. We derive these optimal weights for both Gradient Descent and Adam optimizers. To ensure scalability and reduce computational cost, we propose a \\(\textit\{landmark-based approximation\}\\): influence is precisely computed for a small subset of "landmark" samples and then efficiently propagated to all other samples to determine their weights. We validate Influence Distillation by applying it to instruction tuning on the Tulu V2 dataset, targeting a range of tasks including GSM8k, SQuAD, and MMLU, across several models from the Llama and Qwen families. Experiments show that Influence Distillation matches or outperforms state-of-the-art performance while achieving up to \\(3.5\times\\) faster selection.
