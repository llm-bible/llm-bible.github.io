---
layout: publication
title: 'Training Long-context Llms Efficiently Via Chunk-wise Optimization'
authors: Wenhao Li, Yuxin Zhang, Gen Luo, Daohai Yu, Rongrong Ji
conference: "Arxiv"
year: 2025
bibkey: li2025training
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.16710'}
  - {name: "Code", url: 'https://github.com/wenhaoli-xmu/seco}{here'}
tags: ['Has Code', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Ethics and Bias', 'Pretraining Methods']
---
While long-context large language models (LLMs) exhibit remarkable document processing capabilities, their prohibitively high training costs often hinder customized applications. To mitigate this issue, we propose \textit\{Sequential Chunk-wise Optimization\} (SeCO), a memory-efficient training paradigm that partitions lengthy inputs into manageable chunks. Each chunk independently constructs its computational graph and performs localized backpropagation, ensuring that only one chunk's forward activations are stored in memory. Building on SeCO, we further introduce \textit\{Sparse Chunk-wise Optimization\} (SpaCO), which reduces computational overhead by selectively propagating gradients to specific chunks and incorporates a carefully designed compensation factor to ensure unbiased gradient estimation. SpaCO decouples the computational cost of backpropagation from the context length, enabling training time to gradually converge to inference time as sequences become longer. Implemented as lightweight training wrappers, both SeCO and SpaCO offer substantial practical benefits. For example, when fine-tuning an 8B model with LoRA on a single RTX 3090 GPU, SeCO expands maximum sequence length from 1K to 16K tokens, while SpaCO demonstrates accelerated training speed -- achieving up to 3x faster than SeCO under the same experimental setup. These innovations provide new insights into optimizing long-context models, making them more accessible for practical applications. We have open-sourced the code at \href\{https://github.com/wenhaoli-xmu/seco\}\{here\}.
