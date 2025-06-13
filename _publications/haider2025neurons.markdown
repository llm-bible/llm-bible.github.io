---
layout: publication
title: 'Neurons Speak In Ranges: Breaking Free From Discrete Neuronal Attribution'
authors: Muhammad Umair Haider, Hammad Rizwan, Hassan Sajjad, Peizhong Ju, A. B. Siddique
conference: "Arxiv"
year: 2025
bibkey: haider2025neurons
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.06809'}
tags: ['Reinforcement Learning', 'Interpretability and Explainability', 'Tools']
---
Interpreting the internal mechanisms of large language models (LLMs) is crucial for improving their trustworthiness and utility. Prior work has primarily focused on mapping individual neurons to discrete semantic concepts. However, such mappings struggle to handle the inherent polysemanticity in LLMs, where individual neurons encode multiple, distinct concepts. Through a comprehensive analysis of both encoder and decoder-based LLMs across diverse datasets, we observe that even highly salient neurons, identified via various attribution techniques for specific semantic concepts, consistently exhibit polysemantic behavior. Importantly, activation magnitudes for fine-grained concepts follow distinct, often Gaussian-like distributions with minimal overlap. This observation motivates a shift from neuron attribution to range-based interpretation. We hypothesize that interpreting and manipulating neuron activation ranges would enable more precise interpretability and targeted interventions in LLMs. To validate our hypothesis, we introduce NeuronLens, a novel range-based interpretation and manipulation framework that provides a finer view of neuron activation distributions to localize concept attribution within a neuron. Extensive empirical evaluations demonstrate that NeuronLens significantly reduces unintended interference, while maintaining precise manipulation of targeted concepts, outperforming neuron attribution.
