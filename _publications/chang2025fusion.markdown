---
layout: publication
title: 'Fusion Steering: Prompt-specific Activation Control'
authors: Waldemar Chang, Alhassan Yasin
conference: "Arxiv"
year: 2025
bibkey: chang2025fusion
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22572"}
tags: ['Transformer', 'Efficiency and Optimization', 'Interpretability and Explainability', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Pretraining Methods', 'Quantization', 'Prompting']
---
We present Fusion Steering, an activation steering methodology that improves factual accuracy in large language models (LLMs) for question-answering (QA) tasks. This approach introduces flexible steering configurations, including full-layer steering and segmented steering. Unlike traditional methods constrained to single-layer or fixed-layer operations, Fusion Steering employs dynamic injection of prompt-specific activation deltas across all transformer layers. These activation deltas are derived from reference completions that combine the ground-truth answer with a model-generated explanation to facilitate semantically enriched, example-specific steering. The injection weights are optimized per prompt using Optuna, targeting a joint objective that balances token overlap (factual alignment) and perplexity (fluency proxy). Evaluation employs a composite score integrating token overlap and LLM-graded quality, encompassing factual accuracy, coherence, and relevance. Empirical results on 260 SimpleQA prompts (selected from 500 where the baseline failed) showcase the efficacy of segmented steering. Using Gemma-2-2B-IT with 8-bit quantization, segmented steering achieves an accuracy of 25.4% (outputs scoring \\(\geq 0.6\\)), outperforming the baseline at 3.5% and full-layer steering at 16.2%. Under the stricter SimpleQA rubric, segmented steering boosts fully correct responses from 0.0% to 13.1%. These findings highlight the strengths of segmented, dynamic intervention strategies and the promise of per-prompt, full-network activation control. Fusion Steering is also amenable to sparse representations, such as Neuronpedia or sparse crosscoders, suggesting a promising direction for interpretable and scalable activation-level control in LLMs.
