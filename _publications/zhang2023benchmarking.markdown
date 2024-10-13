---
layout: publication
title: 'Benchmarking And In-depth Performance Study Of Large Language Models On Habana Gaudi Processors'
authors: Zhang Chengming, Sun Baixi, Yu Xiaodong, Xie Zhen, Zheng Weijian, Iskra Kamil, Beckman Pete, Tao Dingwen
conference: "Arxiv"
year: 2023
bibkey: zhang2023benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.16976"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Transformer models have achieved remarkable success in various machine
learning tasks but suffer from high computational complexity and resource
requirements. The quadratic complexity of the self-attention mechanism further
exacerbates these challenges when dealing with long sequences and large
datasets. Specialized AI hardware accelerators, such as the Habana GAUDI
architecture, offer a promising solution to tackle these issues. GAUDI features
a Matrix Multiplication Engine (MME) and a cluster of fully programmable Tensor
Processing Cores (TPC). This paper explores the untapped potential of using
GAUDI processors to accelerate Transformer-based models, addressing key
challenges in the process. Firstly, we provide a comprehensive performance
comparison between the MME and TPC components, illuminating their relative
strengths and weaknesses. Secondly, we explore strategies to optimize MME and
TPC utilization, offering practical insights to enhance computational
efficiency. Thirdly, we evaluate the performance of Transformers on GAUDI,
particularly in handling long sequences and uncovering performance bottlenecks.
Lastly, we evaluate the end-to-end performance of two Transformer-based large
language models (LLM) on GAUDI. The contributions of this work encompass
practical insights for practitioners and researchers alike. We delve into
GAUDI's capabilities for Transformers through systematic profiling, analysis,
and optimization exploration. Our study bridges a research gap and offers a
roadmap for optimizing Transformer-based model training on the GAUDI
architecture.
