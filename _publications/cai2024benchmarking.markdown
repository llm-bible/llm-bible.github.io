---
layout: publication
title: 'Temporalbench: Benchmarking Fine-grained Temporal Understanding For Multimodal Video Models'
authors: Mu Cai, Reuben Tan, Jianrui Zhang, Bocheng Zou, Kai Zhang, Feng Yao, Fangrui Zhu, Jing Gu, Yiwu Zhong, Yuzhang Shang, Yao Dou, Jaden Park, Jianfeng Gao, Yong Jae Lee, Jianwei Yang
conference: "Arxiv"
year: 2024
bibkey: cai2024benchmarking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.10818'}
tags: ['Language Modeling', 'GPT', 'Applications', 'Model Architecture', 'Multimodal Models', 'Ethics and Bias']
---
Understanding fine-grained temporal dynamics is crucial for multimodal video
comprehension and generation. Due to the lack of fine-grained temporal
annotations, existing video benchmarks mostly resemble static image benchmarks
and are incompetent at evaluating models for temporal understanding. In this
paper, we introduce TemporalBench, a new benchmark dedicated to evaluating
fine-grained temporal understanding in videos. TemporalBench consists of ~10K
video question-answer pairs, derived from ~2K high-quality human annotations
detailing the temporal dynamics in video clips. As a result, our benchmark
provides a unique testbed for evaluating various temporal understanding and
reasoning abilities such as action frequency, motion magnitude, event order,
etc. Moreover, it enables evaluations on various tasks like both video question
answering and captioning, both short and long video understanding, as well as
different models such as multimodal video embedding models and text generation
models. Results show that state-of-the-art models like GPT-4o achieve only
38.5% question answering accuracy on TemporalBench, demonstrating a significant
gap (~30%) between humans and AI in temporal understanding. Furthermore, we
notice a critical pitfall for multi-choice QA where LLMs can detect the subtle
changes in negative captions and find a centralized description as a cue for
its prediction, where we propose Multiple Binary Accuracy (MBA) to correct such
bias. We hope that TemporalBench can foster research on improving models'
temporal reasoning capabilities. Both dataset and evaluation code will be made
available.
