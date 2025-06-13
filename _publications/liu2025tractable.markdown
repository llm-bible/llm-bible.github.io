---
layout: publication
title: 'Tractable Transformers For Flexible Conditional Generation'
authors: Anji Liu, Xuejie Liu, Dayuan Zhao, Mathias Niepert, Yitao Liang, Guy Van Den Broeck
conference: "Arxiv"
year: 2025
bibkey: liu2025tractable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.07616"}
tags: ['Training Techniques', 'Model Architecture', 'Merging', 'GPT', 'Pretraining Methods', 'Transformer']
---
Non-autoregressive (NAR) generative models are valuable because they can
handle diverse conditional generation tasks in a more principled way than their
autoregressive (AR) counterparts, which are constrained by sequential
dependency requirements. Recent advancements in NAR models, such as diffusion
language models, have demonstrated superior performance in unconditional
generation compared to AR models (e.g., GPTs) of similar sizes. However, such
improvements do not always lead to improved conditional generation performance.
We show that a key reason for this gap is the difficulty in generalizing to
conditional probability queries unseen during training. As a result, strong
unconditional generation performance does not guarantee high-quality
conditional generation. This paper proposes Tractable Transformers
(Tracformer), a Transformer-based generative model that is more robust to
different conditional generation tasks. Unlike existing models that rely solely
on global contextual features derived from full inputs, Tracformers incorporate
a sparse Transformer encoder to capture both local and global contextual
information. This information is routed through a decoder for conditional
generation. Empirical results demonstrate that Tracformers achieve
state-of-the-art conditional generation performance on text modeling compared
to recent diffusion and AR model baselines.
