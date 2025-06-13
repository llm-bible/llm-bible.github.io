---
layout: publication
title: 'Cola: Compute-efficient Pre-training Of Llms Via Low-rank Activation'
authors: Ziyue Liu, Ruijie Zhang, Zhengyang Wang, Zi Yang, Paul Hovland, Bogdan Nicolae, Franck Cappello, Zheng Zhang
conference: "Arxiv"
year: 2025
bibkey: liu2025compute
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.10940"}
tags: ['Pre-Training', 'Efficiency and Optimization', 'Tools', 'Model Architecture', 'Training Techniques', 'Attention Mechanism']
---
The full-size MLPs and the projection layers in attention introduce tremendous model sizes of large language models (LLMs), imposing extremely demanding needs of computational resources in the pre-training stage. However, we empirically observe that the activations of pre-trained LLMs exhibit low-rank property. Motivated by such observations, we propose CoLA and its memory-efficient implementation, CoLA-M, to replace these full-size layers with compute-efficient auto-encoders that naturally enforce low-rank activations throughout training. This fundamental architectural change eliminates the activation redundancy and significantly boosts model capacity and training efficiency. Experiments on LLaMA models with 60 million to 7 billion parameters show that CoLA reduces the computing cost by \\(\bf 2\pmb\{\times\}\\) and improves training throughput by \\(\bf 1.86\pmb\{\times\}\\) while maintaining full-rank level performance. CoLA-M further squeezes memory cost without sacrificing throughput, offering a pre-training approach with collectively superior parameter, computing, and memory efficiency. The LLMs produced are also \\(\bf 2\pmb\{\times\}\\) smaller, enabling faster inference with lower memory cost on resource-constrained platforms.
