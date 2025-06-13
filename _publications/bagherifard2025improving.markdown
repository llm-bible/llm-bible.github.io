---
layout: publication
title: 'Genknowsub: Improving Modularity And Reusability Of Llms Through General Knowledge Subtraction'
authors: Mohammadtaha Bagherifard, Sahar Rajabi, Ali Edalat, Yadollah Yaghoobzadeh
conference: "Arxiv"
year: 2025
bibkey: bagherifard2025improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.10939'}
  - {name: "Code", url: 'https://github.com/saharsamr/Modular-LLM'}
tags: ['Has Code', 'RAG', 'Training Techniques', 'Tools', 'Fine-Tuning']
---
Large language models often struggle with zero-shot generalization, and several modular approaches have been proposed to address this challenge. Yet, we hypothesize that a key limitation remains: the entanglement of general knowledge and task-specific adaptations. To overcome this, we propose a modular framework that disentangles these components by constructing a library of task-specific LoRA modules alongside a general-domain LoRA. By subtracting this general knowledge component from each task-specific module, we obtain residual modules that focus more exclusively on task-relevant information, a method we call general knowledge subtraction (GenKnowSub). Leveraging the refined task-specific modules and the Arrow routing algorithm \citep\{ostapenko2024towards\}, we dynamically select and combine modules for new inputs without additional training. Our studies on the Phi-3 model and standard Arrow as baselines reveal that using general knowledge LoRAs derived from diverse languages, including English, French, and German, yields consistent performance gains in both monolingual and cross-lingual settings across a wide set of benchmarks. Further experiments on Phi-2 demonstrate how GenKnowSub generalizes to weaker LLMs. The complete code and data are available at https://github.com/saharsamr/Modular-LLM.
