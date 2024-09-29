---
layout: publication
title: Towards Robust Instruction Tuning on Multimodal Large Language Models
authors: Han Wei, Chen Hui, Poria Soujanya
conference: "Arxiv"
year: 2024
bibkey: han2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14492"}
tags: ['Fine Tuning', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques']
---
Fine-tuning large language models (LLMs) on multi-task instruction-following data has been proven to be a powerful learning paradigm for improving their zero-shot capabilities on new tasks. Recent works about high-quality instruction-following data generation and selection require amounts of human labor to conceive model-understandable instructions for the given tasks and carefully filter the LLM-generated data. In this work we introduce an automatic instruction augmentation method named INSTRAUG in multimodal tasks. It starts from a handful of basic and straightforward meta instructions but can expand an instruction-following dataset by 30 times. Results on two popular multimodal instructionfollowing benchmarks MULTIINSTRUCT and InstructBLIP show that INSTRAUG can significantly improve the alignment of multimodal large language models (MLLMs) across 12 multimodal tasks which is even equivalent to the benefits of scaling up training data multiple times.
