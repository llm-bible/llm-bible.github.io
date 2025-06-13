---
layout: publication
title: 'Amazon Sagemaker Model Parallelism: A General And Flexible Framework For Large Model Training'
authors: Can Karakus, Rahul Huilgol, Fei Wu, Anirudh Subramanian, Cade Daniel, Derya Cavdar, Teng Xu, Haohan Chen, Arash Rahnama, Luis Quintela
conference: "Arxiv"
year: 2021
bibkey: karakus2021amazon
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2111.05972"}
tags: ['Tools', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'BERT']
---
With deep learning models rapidly growing in size, systems-level solutions
for large-model training are required. We present Amazon SageMaker model
parallelism, a software library that integrates with PyTorch, and enables easy
training of large models using model parallelism and other memory-saving
features. In contrast to existing solutions, the implementation of the
SageMaker library is much more generic and flexible, in that it can
automatically partition and run pipeline parallelism over arbitrary model
architectures with minimal code change, and also offers a general and
extensible framework for tensor parallelism, which supports a wider range of
use cases, and is modular enough to be easily applied to new training scripts.
The library also preserves the native PyTorch user experience to a much larger
degree, supporting module re-use and dynamic graphs, while giving the user full
control over the details of the training step. We evaluate performance over
GPT-3, RoBERTa, BERT, and neural collaborative filtering, and demonstrate
competitive performance over existing solutions.
