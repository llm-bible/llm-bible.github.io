---
layout: publication
title: 'Lv-xattn: Distributed Cross-attention For Long Visual Inputs In Multimodal Large Language Models'
authors: Tzu-tao Chang, Shivaram Venkataraman
conference: "Arxiv"
year: 2025
bibkey: chang2025lv
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.02406"}
tags: ['Transformer', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Multimodal Models']
---
Cross-attention is commonly adopted in multimodal large language models (MLLMs) for integrating visual information into the language backbone. However, in applications with large visual inputs, such as video understanding, processing a large number of visual tokens in cross-attention layers leads to high memory demands and often necessitates distributed computation across multiple GPUs. Existing distributed attention mechanisms face significant communication overheads, making cross-attention layers a critical bottleneck for efficient training and inference of MLLMs. To address this, we propose LV-XAttn, a distributed, exact cross-attention mechanism with minimal communication overhead. We observe that in applications involving large visual inputs, the size of the query block is typically much smaller than that of the key-value blocks. Thus, in LV-XAttn we keep the large key-value blocks locally on each GPU and exchange smaller query blocks across GPUs. We also introduce an efficient activation recomputation technique to support longer visual context. We theoretically analyze the communication benefits of LV-XAttn and show that it can achieve speedups for a wide range of models. Our evaluations with Llama 3-V, mPLUG-Owl3 and OpenFlamingo models find that LV-XAttn achieves up to 10.62\\(\times\\) end-to-end speedup compared to existing approaches.
