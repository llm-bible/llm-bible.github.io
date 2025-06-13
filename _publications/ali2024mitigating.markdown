---
layout: publication
title: 'Mitigating Copy Bias In In-context Learning Through Neuron Pruning'
authors: Ameen Ali, Lior Wolf, Ivan Titov
conference: "Arxiv"
year: 2024
bibkey: ali2024mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.01288"}
tags: ['Transformer', 'Efficiency and Optimization', 'Ethics and Bias', 'Model Architecture', 'Reinforcement Learning', 'Pruning', 'Pretraining Methods', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) have demonstrated impressive few-shot in-context
learning (ICL) abilities. Still, we show that they are sometimes prone to a
`copying bias', where they copy answers from provided examples instead of
learning the underlying patterns. In this work, we propose a novel and simple
method to mitigate such copying bias. First, we create a synthetic task and use
the Integrated Gradients method to identify neurons that prioritize copying
over generalization. We demonstrate that pruning these neurons consistently
improves performance across a diverse set of ICL tasks. We also show that our
method is applicable across various LLM architectures, including Transformers
and State-Space Models, without requiring modifications. In our analysis, we
adopt a task-recognition perspective on ICL and examine task vectors (Hendel et
al., 2023) induced by the model. We find that pruning enhances the quality of
these vectors, suggesting that the pruned neurons previously hindered effective
task recognition.
