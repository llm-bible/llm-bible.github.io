---
layout: publication
title: 'Reasonplan: Unified Scene Prediction And Decision Reasoning For Closed-loop Autonomous Driving'
authors: Xueyi Liu, Zuodong Zhong, Yuxin Guo, Yun-fu Liu, Zhiguo Su, Qichao Zhang, Junli Wang, Yinfeng Gao, Yupeng Zheng, Qiao Lin, Huiyong Chen, Dongbin Zhao
conference: "Arxiv"
year: 2025
bibkey: liu2025unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20024"}
  - {name: "Code", url: "https://github.com/Liuxueyi/ReasonPlan"}
tags: ['Fine-Tuning', 'Tools', 'RAG', 'Model Architecture', 'Interpretability', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods', 'Multimodal Models']
---
Due to the powerful vision-language reasoning and generalization abilities, multimodal large language models (MLLMs) have garnered significant attention in the field of end-to-end (E2E) autonomous driving. However, their application to closed-loop systems remains underexplored, and current MLLM-based methods have not shown clear superiority to mainstream E2E imitation learning approaches. In this work, we propose ReasonPlan, a novel MLLM fine-tuning framework designed for closed-loop driving through holistic reasoning with a self-supervised Next Scene Prediction task and supervised Decision Chain-of-Thought process. This dual mechanism encourages the model to align visual representations with actionable driving context, while promoting interpretable and causally grounded decision making. We curate a planning-oriented decision reasoning dataset, namely PDR, comprising 210k diverse and high-quality samples. Our method outperforms the mainstream E2E imitation learning method by a large margin of 19% L2 and 16.1 driving score on Bench2Drive benchmark. Furthermore, ReasonPlan demonstrates strong zero-shot generalization on unseen DOS benchmark, highlighting its adaptability in handling zero-shot corner cases. Code and dataset will be found in https://github.com/Liuxueyi/ReasonPlan.
