---
layout: publication
title: OmniJARVIS Unified Vision-Language-Action Tokenization Enables Open-World Instruction Following Agents
authors: Wang Zihao, Cai Shaofei, Mu Zhancun, Lin Haowei, Zhang Ceyao, Liu Xuejie, Li Qing, Liu Anji, Ma Xiaojian, Liang Yitao
conference: "Arxiv"
year: 2024
bibkey: wang2024omnijarvis
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00114"}
tags: ['Agentic', 'GPT', 'Masked Language Model', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Tokenization', 'Training Techniques', 'Transformer']
---
We present OmniJARVIS a novel Vision-Language-Action (VLA) model for open-world instruction-following agents in open-world Minecraft. Compared to prior works that either emit textual goals to separate controllers or produce the control command directly OmniJARVIS seeks a different path to ensure both strong reasoning and efficient decision-making capabilities via unified tokenization of multimodal interaction data. First we introduce a self-supervised approach to learn a behavior encoder that produces discretized tokens for behavior trajectories τ = o_0 a_0 and an imitation learning (IL) policy decoder conditioned on these tokens. These additional behavior tokens will be augmented to the vocabulary of pretrained Multimodal Language Models (MLMs). With this encoder we then pack long-term multimodal interactions involving task instructions memories thoughts observations textual responses behavior trajectories etc. into unified token sequences and model them with autoregressive transformers. Thanks to the semantically meaningful behavior tokens the resulting VLA model OmniJARVIS can reason (by producing chain-of-thoughts) plan answer questions and act (by producing behavior tokens for the IL policy decoder). OmniJARVIS demonstrates excellent performances on a comprehensive collection of atomic programmatic and open-ended tasks in open-world Minecraft. Our analysis further unveils the crucial design principles in interaction data formation unified tokenization and its scaling potentials.
