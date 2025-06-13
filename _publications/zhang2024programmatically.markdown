---
layout: publication
title: 'Provision: Programmatically Scaling Vision-centric Instruction Data For Multimodal Language Models'
authors: Jieyu Zhang, Le Xue, Linxin Song, Jun Wang, Weikai Huang, Manli Shu, An Yan, Zixian Ma, Juan Carlos Niebles, Silvio Savarese, Caiming Xiong, Zeyuan Chen, Ranjay Krishna, Ran Xu
conference: "Arxiv"
year: 2024
bibkey: zhang2024programmatically
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.07012"}
tags: ['Masked Language Model', 'Multimodal Models', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Interpretability and Explainability', 'Pre-Training', 'Applications']
---
With the rise of multimodal applications, instruction data has become
critical for training multimodal language models capable of understanding
complex image-based queries. Existing practices rely on powerful but costly
large language models (LLMs) or multimodal language models (MLMs) to produce
instruction data. These are often prone to hallucinations, licensing issues and
the generation process is often hard to scale and interpret. In this work, we
present a programmatic approach that employs scene graphs as symbolic
representations of images and human-written programs to systematically
synthesize vision-centric instruction data. Our approach ensures the
interpretability and controllability of the data generation process and scales
efficiently while maintaining factual accuracy. By implementing a suite of 24
single-image, 14 multi-image instruction generators, and a scene graph
generation pipeline, we build a scalable, cost-effective system: ProVision
which produces diverse question-answer pairs concerning objects, attributes,
relations, depth, etc., for any given image. Applied to Visual Genome and
DataComp datasets, we generate over 10 million instruction data points,
ProVision-10M, and leverage them in both pretraining and instruction tuning
stages of MLMs. When adopted in the instruction tuning stage, our single-image
instruction data yields up to a 7% improvement on the 2D split and 8% on the 3D
split of CVBench, along with a 3% increase in performance on QBench2,
RealWorldQA, and MMMU. Our multi-image instruction data leads to an 8%
improvement on Mantis-Eval. Incorporation of our data in both pre-training and
fine-tuning stages of xGen-MM-4B leads to an averaged improvement of 1.6%
across 11 benchmarks.
