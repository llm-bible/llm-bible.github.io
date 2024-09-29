---
layout: publication
title: Mm45;narrator Narrating Long45;form Videos With Multimodal In45;context Learning
authors: Zhang Chaoyi, Lin Kevin, Yang Zhengyuan, Wang Jianfeng, Li Linjie, Lin Chung-ching, Liu Zicheng, Wang Lijuan
conference: "Arxiv"
year: 2023
bibkey: zhang2023mm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.17435"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
We present MM45;Narrator a novel system leveraging GPT45;4 with multimodal in45;context learning for the generation of audio descriptions (AD). Unlike previous methods that primarily focused on downstream fine45;tuning with short video clips MM45;Narrator excels in generating precise audio descriptions for videos of extensive lengths even beyond hours in an autoregressive manner. This capability is made possible by the proposed memory45;augmented generation process which effectively utilizes both the short45;term textual context and long45;term visual memory through an efficient register45;and45;recall mechanism. These contextual memories compile pertinent past information including storylines and character identities ensuring an accurate tracking and depicting of story45;coherent and character45;centric audio descriptions. Maintaining the training45;free design of MM45;Narrator we further propose a complexity45;based demonstration selection strategy to largely enhance its multi45;step reasoning capability via few45;shot multimodal in45;context learning (MM45;ICL). Experimental results on MAD45;eval dataset demonstrate that MM45;Narrator consistently outperforms both the existing fine45;tuning45;based approaches and LLM45;based approaches in most scenarios as measured by standard evaluation metrics. Additionally we introduce the first segment45;based evaluator for recurrent text generation. Empowered by GPT45;4 this evaluator comprehensively reasons and marks AD generation performance in various extendable dimensions.
