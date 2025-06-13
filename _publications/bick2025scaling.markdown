---
layout: publication
title: 'Llamba: Scaling Distilled Recurrent Models For Efficient Language Processing'
authors: Aviv Bick, Tobias Katsch, Nimit Sohoni, Arjun Desai, Albert Gu
conference: "Arxiv"
year: 2025
bibkey: bick2025scaling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.14458'}
tags: ['Transformer', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Model Architecture', 'Tools', 'Pretraining Methods']
---
We introduce Llamba, a family of efficient recurrent language models
distilled from Llama-3.x into the Mamba architecture. The series includes
Llamba-1B, Llamba-3B, and Llamba-8B, which achieve higher inference throughput
and handle significantly larger batch sizes than Transformer-based models while
maintaining comparable benchmark performance. Furthermore, Llamba demonstrates
the effectiveness of cross-architecture distillation using MOHAWK (Bick et al.,
2024), achieving these results with less than 0.1% of the training data
typically used for models of similar size. To take full advantage of their
efficiency, we provide an optimized implementation of Llamba for
resource-constrained devices such as smartphones and edge platforms, offering a
practical and memory-efficient alternative to Transformers. Overall, Llamba
improves the tradeoff between speed, memory efficiency, and performance, making
high-quality language models more accessible.
