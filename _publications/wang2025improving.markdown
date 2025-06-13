---
layout: publication
title: 'Improving Model Alignment Through Collective Intelligence Of Open-source LLMS'
authors: Junlin Wang, Roy Xie, Shang Zhu, Jue Wang, Ben Athiwaratkun, Bhuwan Dhingra, Shuaiwen Leon Song, Ce Zhang, James Zou
conference: "Arxiv"
year: 2025
bibkey: wang2025improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.03059'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'GPT', 'Pretraining Methods']
---
Building helpful and harmless large language models (LLMs) requires effective
model alignment approach based on human instructions and feedback, which
necessitates high-quality human-labeled data. Constructing such datasets is
often expensive and hard to scale, and may face potential limitations on
diversity and generalization. To address these challenges, we introduce Mixture
of Agents Alignment (MoAA), that leverages the collective strengths of various
language models to provide high-quality data for model alignment. By employing
MoAA, we enhance both supervised fine-tuning and preference optimization,
leading to improved performance compared to using a single model alone to
generate alignment data (e.g. using GPT-4o alone). Evaluation results show that
our approach can improve win rate of LLaMA-3.1-8B-Instruct from 19.5 to 48.3 on
Arena-Hard and from 22.33 to 57.23 on AlpacaEval2, highlighting a promising
direction for model alignment through this new scalable and diverse synthetic
data recipe. Furthermore, we demonstrate that MoAA enables a self-improvement
pipeline, where models finetuned on MoA-generated data surpass their own
initial capabilities, providing evidence that our approach can push the
frontier of open-source LLMs without reliance on stronger external supervision.
Data and code will be released.
