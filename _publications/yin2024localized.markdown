---
layout: publication
title: Lofit: Localized Fine-tuning On LLM Representations
authors: Yin Fangcong, Ye Xi, Durrett Greg
conference: "Arxiv"
year: 2024
bibkey: yin2024localized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.01563"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Fine Tuning', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Recent work in interpretability shows that large language models (LLMs) can be adapted for new tasks in a learning-free way it is possible to intervene on LLM representations to elicit desired behaviors for alignment. For instance adding certain bias vectors to the outputs of certain attention heads is reported to boost the truthfulness of models. In this work we show that localized fine-tuning serves as an effective alternative to such representation intervention methods. We introduce a framework called Localized Fine-Tuning on LLM Representations (LoFiT) which identifies a subset of attention heads that are most important for learning a specific task then trains offset vectors to add to the models hidden representations at those selected heads. LoFiT localizes to a sparse set of heads (337;) and learns the offset vectors from limited training data comparable to the settings used for representation intervention. For truthfulness and reasoning tasks we find that LoFiTs intervention vectors are more effective for LLM adaptation than vectors from representation intervention methods such as Inference-time Intervention. We also find that the localization step is important selecting a task-specific set of attention heads can lead to higher performance than intervening on heads selected for a different task. Finally for the tasks we study LoFiT achieves comparable performance to other parameter-efficient fine-tuning methods such as LoRA despite modifying 20x-200x fewer parameters than these methods.
