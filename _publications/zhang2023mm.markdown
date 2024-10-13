---
layout: publication
title: 'Mm-narrator: Narrating Long-form Videos With Multimodal In-context Learning'
authors: Zhang Chaoyi, Lin Kevin, Yang Zhengyuan, Wang Jianfeng, Li Linjie, Lin Chung-ching, Liu Zicheng, Wang Lijuan
conference: "Arxiv"
year: 2023
bibkey: zhang2023mm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.17435"}
tags: ['Applications', 'Few Shot', 'Fine Tuning', 'GPT', 'In Context Learning', 'Language Modeling', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
We present MM-Narrator, a novel system leveraging GPT-4 with multimodal
in-context learning for the generation of audio descriptions (AD). Unlike
previous methods that primarily focused on downstream fine-tuning with short
video clips, MM-Narrator excels in generating precise audio descriptions for
videos of extensive lengths, even beyond hours, in an autoregressive manner.
This capability is made possible by the proposed memory-augmented generation
process, which effectively utilizes both the short-term textual context and
long-term visual memory through an efficient register-and-recall mechanism.
These contextual memories compile pertinent past information, including
storylines and character identities, ensuring an accurate tracking and
depicting of story-coherent and character-centric audio descriptions.
Maintaining the training-free design of MM-Narrator, we further propose a
complexity-based demonstration selection strategy to largely enhance its
multi-step reasoning capability via few-shot multimodal in-context learning
(MM-ICL). Experimental results on MAD-eval dataset demonstrate that MM-Narrator
consistently outperforms both the existing fine-tuning-based approaches and
LLM-based approaches in most scenarios, as measured by standard evaluation
metrics. Additionally, we introduce the first segment-based evaluator for
recurrent text generation. Empowered by GPT-4, this evaluator comprehensively
reasons and marks AD generation performance in various extendable dimensions.
