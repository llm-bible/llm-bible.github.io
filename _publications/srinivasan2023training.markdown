---
layout: publication
title: Training Large Language Models Efficiently with Sparsity and Dataflow
authors: Srinivasan Venkat, Gandhi Darshan, Thakker Urmish, Prabhakar Raghu
conference: "Arxiv"
year: 2023
bibkey: srinivasan2023training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.05511"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Merging', 'Model Architecture', 'Training Techniques']
---
Large foundation language models have shown their versatility in being able to be adapted to perform a wide variety of downstream tasks such as text generation sentiment analysis semantic search etc. However training such large foundational models is a non-trivial exercise that requires a significant amount of compute power and expertise from machine learning and systems experts. As models get larger these demands are only increasing. Sparsity is a promising technique to relieve the compute requirements for training. However sparsity introduces new challenges in training the sparse model to the same quality as the dense counterparts. Furthermore sparsity drops the operation intensity and introduces irregular memory access patterns that makes it challenging to efficiently utilize compute resources. This paper demonstrates an end-to-end training flow on a large language model - 13 billion GPT - using sparsity and dataflow. The dataflow execution model and architecture enables efficient on-chip irregular memory accesses as well as native kernel fusion and pipelined parallelism that helps recover device utilization. We show that we can successfully train GPT 13B to the same quality as the dense GPT 13B model while achieving an end-end speedup of 4.5x over dense A100 baseline.
