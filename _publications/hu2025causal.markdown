---
layout: publication
title: 'Causal-llava: Causal Disentanglement For Mitigating Hallucination In Multimodal Large Language Models'
authors: Xinmiao Zhejiang University Hu, Chun Zhejiang University Wang, Ruihe Zhejiang University An, Chenyu Zhejiang University Shao, Xiaojun Zhejiang University Ye, Sheng Zhejiang University Zhou, Liangcheng Zhejiang University Li
conference: "Arxiv"
year: 2025
bibkey: hu2025causal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.19474"}
  - {name: "Code", url: "https://github.com/IgniSavium/Causal-LLaVA"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Tools', 'Ethics and Bias', 'Pretraining Methods', 'Transformer', 'Has Code']
---
Multimodal Large Language Models (MLLMs) have demonstrated strong performance in visual understanding tasks, yet they often suffer from object hallucinations--generating descriptions of objects that are inconsistent with or entirely absent from the input. This issue is closely related to dataset biases, where frequent co-occurrences of objects lead to entangled semantic representations across modalities. As a result, models may erroneously activate object representations that are commonly associated with the input but not actually present.
  To address this, we propose a causality-driven disentanglement framework that mitigates hallucinations through causal intervention. Our approach includes a Causal-Driven Projector in the visual pathway and a Causal Intervention Module integrated into the final transformer layer of the language model. These components work together to reduce spurious correlations caused by biased training data.
  Experimental results show that our method significantly reduces hallucinations while maintaining strong performance on multiple multimodal benchmarks. Visualization analyses further confirm improved separability of object representations.
  The code is available at: https://github.com/IgniSavium/Causal-LLaVA
