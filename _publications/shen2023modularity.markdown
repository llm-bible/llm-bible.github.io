---
layout: publication
title: 'Moduleformer: Modularity Emerges From Mixture-of-experts'
authors: Yikang Shen, Zheyu Zhang, Tianyou Cao, Shawn Tan, Zhenfang Chen, Chuang Gan
conference: "Arxiv"
year: 2023
bibkey: shen2023modularity
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2306.04640'}
tags: ['Attention Mechanism', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pre-Training']
---
Large Language Models (LLMs) have achieved remarkable results. However,
existing models are expensive to train and deploy, and it is also difficult to
expand their knowledge beyond pre-training data without forgetting previous
knowledge. This paper proposes a new neural network architecture, ModuleFormer,
that leverages modularity to improve the efficiency and flexibility of large
language models. ModuleFormer is based on the Sparse Mixture of Experts (SMoE).
Unlike the previous SMoE-based modular language model, which requires
domain-labeled data to learn domain-specific experts, ModuleFormer can induce
modularity from uncurated data with its new load balancing and concentration
losses. ModuleFormer is a modular architecture that includes two different
types of modules: new stick-breaking attention heads and feedforward experts.
Different modules are sparsely activated conditions on the input token during
training and inference. In our experiment, we found that the modular
architecture enables three important abilities for large pre-trained language
models: 1) Efficiency, since ModuleFormer only activates a subset of its
modules for each input token, thus it could achieve the same performance as
dense LLMs with more than two times throughput; 2) Extendability, ModuleFormer
is more immune to catastrophic forgetting than dense LLMs and can be easily
extended with new modules to learn new knowledge that is not included in the
training data; 3) Specialisation, finetuning ModuleFormer could specialize a
subset of modules to the finetuning task and the task-unrelated modules could
be easily pruned for a lightweight deployment.
