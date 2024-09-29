---
layout: publication
title: Unveiling And Mitigating Memorization In Text45;to45;image Diffusion Models Through Cross Attention
authors: Ren Jie, Li Yaxin, Zeng Shenglai, Xu Han, Lyu Lingjuan, Xing Yue, Tang Jiliang
conference: "Arxiv"
year: 2024
bibkey: ren2024unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11052"}
  - {name: "Code", url: "https://github.com/renjie3/MemAttn"}
tags: ['Attention Mechanism', 'Has Code', 'Merging', 'Model Architecture', 'Prompting', 'Training Techniques', 'Transformer']
---
Recent advancements in text45;to45;image diffusion models have demonstrated their remarkable capability to generate high45;quality images from textual prompts. However increasing research indicates that these models memorize and replicate images from their training data raising tremendous concerns about potential copyright infringement and privacy risks. In our study we provide a novel perspective to understand this memorization phenomenon by examining its relationship with cross45;attention mechanisms. We reveal that during memorization the cross45;attention tends to focus disproportionately on the embeddings of specific tokens. The diffusion model is overfitted to these token embeddings memorizing corresponding training images. To elucidate this phenomenon we further identify and discuss various intrinsic findings of cross45;attention that contribute to memorization. Building on these insights we introduce an innovative approach to detect and mitigate memorization in diffusion models. The advantage of our proposed method is that it will not compromise the speed of either the training or the inference processes in these models while preserving the quality of generated images. Our code is available at https://github.com/renjie3/MemAttn .
