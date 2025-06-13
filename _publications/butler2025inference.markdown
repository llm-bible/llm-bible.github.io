---
layout: publication
title: 'Proxyspex: Inference-efficient Interpretability Via Sparse Feature Interactions In Llms'
authors: Landon Butler, Abhineet Agarwal, Justin Singh Kang, Yigit Efe Erginbas, Bin Yu, Kannan Ramchandran
conference: "Arxiv"
year: 2025
bibkey: butler2025inference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17495"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pruning', 'Interpretability and Explainability', 'Attention Mechanism']
---
Large Language Models (LLMs) have achieved remarkable performance by capturing complex interactions between input features. To identify these interactions, most existing approaches require enumerating all possible combinations of features up to a given order, causing them to scale poorly with the number of inputs \\(n\\). Recently, Kang et al. (2025) proposed SPEX, an information-theoretic approach that uses interaction sparsity to scale to \\(n \approx 10^3\\) features. SPEX greatly improves upon prior methods but requires tens of thousands of model inferences, which can be prohibitive for large models. In this paper, we observe that LLM feature interactions are often hierarchical -- higher-order interactions are accompanied by their lower-order subsets -- which enables more efficient discovery. To exploit this hierarchy, we propose ProxySPEX, an interaction attribution algorithm that first fits gradient boosted trees to masked LLM outputs and then extracts the important interactions. Experiments across four challenging high-dimensional datasets show that ProxySPEX more faithfully reconstructs LLM outputs by 20% over marginal attribution approaches while using \\(10\times\\) fewer inferences than SPEX. By accounting for interactions, ProxySPEX identifies features that influence model output over 20% more than those selected by marginal approaches. Further, we apply ProxySPEX to two interpretability tasks. Data attribution, where we identify interactions among CIFAR-10 training samples that influence test predictions, and mechanistic interpretability, where we uncover interactions between attention heads, both within and across layers, on a question-answering task. ProxySPEX identifies interactions that enable more aggressive pruning of heads than marginal approaches.
