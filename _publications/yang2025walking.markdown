---
layout: publication
title: 'Walking The Tightrope: Disentangling Beneficial And Detrimental Drifts In Non-stationary Custom-tuning'
authors: Xiaoyu Yang, Jie Lu, En Yu
conference: "Arxiv"
year: 2025
bibkey: yang2025walking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.13081'}
tags: ['RAG', 'Efficiency and Optimization', 'Security', 'Training Techniques', 'Tools', 'GPT', 'Fine-Tuning', 'Reinforcement Learning', 'Ethics and Bias', 'Pretraining Methods']
---
This paper uncovers a critical yet overlooked phenomenon in multi-modal large language models (MLLMs): detrimental concept drift within chain-of-thought (CoT) reasoning during non-stationary reinforcement fine-tuning (RFT), where reasoning token distributions evolve unpredictably, thereby introducing significant biases in final predictions. To address this, we are pioneers in establishing the theoretical bridge between concept drift theory and RFT processes by formalizing CoT's autoregressive token streams as non-stationary distributions undergoing arbitrary temporal shifts. Leveraging this framework, we propose a novel counterfact-aware RFT that systematically decouples beneficial distribution adaptation from harmful concept drift through concept graph-empowered LLM experts generating counterfactual reasoning trajectories. Our solution, Counterfactual Preference Optimization (CPO), enables stable RFT in non-stationary environments, particularly within the medical domain, through custom-tuning of counterfactual-aware preference alignment. Extensive experiments demonstrate our superior performance of robustness, generalization and coordination within RFT. Besides, we also contributed a large-scale dataset CXR-CounterFact (CCF), comprising 320,416 meticulously curated counterfactual reasoning trajectories derived from MIMIC-CXR. Our code and data are public.
