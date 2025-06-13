---
layout: publication
title: 'Unveiling And Mitigating Memorization In Text-to-image Diffusion Models Through Cross Attention'
authors: Jie Ren, Yaxin Li, Shenglai Zeng, Han Xu, Lingjuan Lyu, Yue Xing, Jiliang Tang
conference: "Arxiv"
year: 2024
bibkey: ren2024unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11052"}
  - {name: "Code", url: "https://github.com/renjie3/MemAttn"}
tags: ['Transformer', 'Model Architecture', 'Merging', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Prompting']
---
Recent advancements in text-to-image diffusion models have demonstrated their
remarkable capability to generate high-quality images from textual prompts.
However, increasing research indicates that these models memorize and replicate
images from their training data, raising tremendous concerns about potential
copyright infringement and privacy risks. In our study, we provide a novel
perspective to understand this memorization phenomenon by examining its
relationship with cross-attention mechanisms. We reveal that during
memorization, the cross-attention tends to focus disproportionately on the
embeddings of specific tokens. The diffusion model is overfitted to these token
embeddings, memorizing corresponding training images. To elucidate this
phenomenon, we further identify and discuss various intrinsic findings of
cross-attention that contribute to memorization. Building on these insights, we
introduce an innovative approach to detect and mitigate memorization in
diffusion models. The advantage of our proposed method is that it will not
compromise the speed of either the training or the inference processes in these
models while preserving the quality of generated images. Our code is available
at https://github.com/renjie3/MemAttn .
