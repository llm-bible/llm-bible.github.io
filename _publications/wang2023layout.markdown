---
layout: publication
title: Docllm A Layout45;aware Generative Language Model For Multimodal Document Understanding
authors: Wang Dongsheng, Raman Natraj, Sibue Mathieu, Ma Zhiqiang, Babkin Petr, Kaur Simerjot, Pei Yulong, Nourbakhsh Armineh, Liu Xiaomo
conference: "Arxiv"
year: 2023
bibkey: wang2023layout
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.00908"}
tags: ['Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Enterprise documents such as forms invoices receipts reports contracts and other similar records often carry rich semantics at the intersection of textual and spatial modalities. The visual cues offered by their complex layouts play a crucial role in comprehending these documents effectively. In this paper we present DocLLM a lightweight extension to traditional large language models (LLMs) for reasoning over visual documents taking into account both textual semantics and spatial layout. Our model differs from existing multimodal LLMs by avoiding expensive image encoders and focuses exclusively on bounding box information to incorporate the spatial layout structure. Specifically the cross45;alignment between text and spatial modalities is captured by decomposing the attention mechanism in classical transformers to a set of disentangled matrices. Furthermore we devise a pre45;training objective that learns to infill text segments. This approach allows us to address irregular layouts and heterogeneous content frequently encountered in visual documents. The pre45;trained model is fine45;tuned using a large45;scale instruction dataset covering four core document intelligence tasks. We demonstrate that our solution outperforms SotA LLMs on 14 out of 16 datasets across all tasks and generalizes well to 4 out of 5 previously unseen datasets.
