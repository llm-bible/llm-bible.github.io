---
layout: publication
title: Skills-in-context Prompting: Unlocking Compositionality In Large Language Models
authors: Chen Jiaao, Pan Xiaoman, Yu Dian, Song Kaiqiang, Wang Xiaoyang, Yu Dong, Chen Jianshu
conference: "Arxiv"
year: 2023
bibkey: chen2023skills
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.00304"}
tags: ['Fine Tuning', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
We investigate how to elicit compositional generalization capabilities in large language models (LLMs). Compositional generalization empowers LLMs to solve complex problems by combining foundational skills a critical reasoning ability akin to human intelligence. However even the most advanced LLMs currently struggle with this form of reasoning. We examine this problem within the framework of in-context learning and find that demonstrating both foundational skills and compositional examples grounded in these skills within the same prompt context is crucial. We refer to this prompt structure as skills-in-context (SKiC). With as few as two exemplars this in-context learning structure enables LLMs to tackle more challenging problems requiring innovative skill combinations achieving near-perfect systematic generalization across a broad range of tasks. Intriguingly SKiC also unlocks the latent potential of LLMs allowing them to more actively utilize pre-existing internal skills acquired during earlier pretraining stages to solve complex reasoning problems. The SKiC structure is robust across different skill constructions and exemplar choices and demonstrates strong transferability to new tasks. Finally inspired by our in-context learning study we show that fine-tuning LLMs with SKiC-style data can elicit zero-shot weak-to-strong generalization enabling the models to solve much harder problems directly with standard prompting.
