---
layout: publication
title: Clover-2&#58; Accurate Inference For Regressive Lightweight Speculative Decoding
authors: Xiao Bin, Gui Lujun, Su Lei, Chen Weipeng
conference: "Arxiv"
year: 2024
bibkey: xiao2024clover
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.00264"}
tags: ['Applications', 'Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Security', 'Transformer']
---
Large Language Models (LLMs) frequently suffer from inefficiencies largely attributable to the discord between the requirements of auto-regressive decoding and the architecture of contemporary GPUs. Recently regressive lightweight speculative decoding has garnered attention for its notable efficiency improvements in text generation tasks. This approach utilizes a lightweight regressive draft model like a Recurrent Neural Network (RNN) or a single transformer decoder layer leveraging sequential information to iteratively predict potential tokens. Specifically RNN draft models are computationally economical but tend to deliver lower accuracy while attention decoder layer models exhibit the opposite traits. This paper presents Clover-2 an advanced iteration of Clover an RNN-based draft model designed to achieve comparable accuracy to that of attention decoder layer models while maintaining minimal computational overhead. Clover-2 enhances the model architecture and incorporates knowledge distillation to increase Clovers accuracy and improve overall efficiency. We conducted experiments using the open-source Vicuna 7B and LLaMA3-Instruct 8B models. The results demonstrate that Clover-2 surpasses existing methods across various model architectures showcasing its efficacy and robustness.
