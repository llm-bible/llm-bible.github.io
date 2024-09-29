---
layout: publication
title: SEP Self-Enhanced Prompt Tuning for Visual-Language Model
authors: Yao Hantao, Zhang Rui, Yu Lu, Xu Changsheng
conference: "Arxiv"
year: 2024
bibkey: yao2024sep
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.15549"}
  - {name: "Code", url: "https://github.com/htyao89/SEP"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Has Code', 'Merging', 'Model Architecture', 'Prompting', 'RAG', 'Transformer']
---
Prompt tuning based on Context Optimization (CoOp) effectively adapts visual-language models (VLMs) to downstream tasks by inferring additional learnable prompt tokens. However these tokens are less discriminative as they are independent of the pre-trained tokens and fail to capture input-specific knowledge such as class-aware textual or instance-aware visual knowledge. Leveraging the discriminative and generalization capabilities inherent in pre-trained tokens we introduce a novel approach named Self-Enhanced Prompt Tuning (SEP). The core principle of SEP involves adapting the learnable prompt tokens at each encoder layer from the corresponding self-pretrained tokens thereby explicitly incorporating discriminative prior knowledge to enhance both textual-level and visual-level embeddings. Furthermore SEPs self-enhanced tokens not only boost discrimination but also mitigate domain shifts in unseen domains enhancing generalization. In practice SEP selects several representative tokens from all pre-trained tokens for each input data at every layer of the text/visual encoders. Subsequently a Token Fusion Module (TFM) is introduced to generate a self-enhanced token by merging these representative tokens with the learnable tokens using a cross-attention mechanism. This self-enhanced token is then concatenated with all pre-trained tokens serving as input for subsequent encoder layers to produce the relevant embeddings. Comprehensive evaluations across various benchmarks and tasks confirm SEPs efficacy in prompt tuning. Code https://github.com/htyao89/SEP}.
