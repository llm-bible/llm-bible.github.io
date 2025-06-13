---
layout: publication
title: 'Chatdit: A Training-free Baseline For Task-agnostic Free-form Chatting With Diffusion Transformers'
authors: Lianghua Huang, Wei Wang, Zhi-fan Wu, Yupeng Shi, Chen Liang, Tong Shen, Han Zhang, Huanzhang Dou, Yu Liu, Jingren Zhou
conference: "Arxiv"
year: 2024
bibkey: huang2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.12571"}
  - {name: "Code", url: "https://github.com/ali-vilab/ChatDiT"}
tags: ['Transformer', 'Agentic', 'Tools', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Merging', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods', 'Arxiv']
---
Recent research arXiv:2410.15027 arXiv:2410.23775 has highlighted the
inherent in-context generation capabilities of pretrained diffusion
transformers (DiTs), enabling them to seamlessly adapt to diverse visual tasks
with minimal or no architectural modifications. These capabilities are unlocked
by concatenating self-attention tokens across multiple input and target images,
combined with grouped and masked generation pipelines. Building upon this
foundation, we present ChatDiT, a zero-shot, general-purpose, and interactive
visual generation framework that leverages pretrained diffusion transformers in
their original form, requiring no additional tuning, adapters, or
modifications. Users can interact with ChatDiT to create interleaved text-image
articles, multi-page picture books, edit images, design IP derivatives, or
develop character design settings, all through free-form natural language
across one or more conversational rounds. At its core, ChatDiT employs a
multi-agent system comprising three key components: an Instruction-Parsing
agent that interprets user-uploaded images and instructions, a
Strategy-Planning agent that devises single-step or multi-step generation
actions, and an Execution agent that performs these actions using an in-context
toolkit of diffusion transformers. We thoroughly evaluate ChatDiT on IDEA-Bench
arXiv:2412.11767, comprising 100 real-world design tasks and 275 cases with
diverse instructions and varying numbers of input and target images. Despite
its simplicity and training-free approach, ChatDiT surpasses all competitors,
including those specifically designed and trained on extensive multi-task
datasets. We further identify key limitations of pretrained DiTs in zero-shot
adapting to tasks. We release all code, agents, results, and intermediate
outputs to facilitate further research at https://github.com/ali-vilab/ChatDiT
