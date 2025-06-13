---
layout: publication
title: 'Gaining Wisdom From Setbacks: Aligning Large Language Models Via Mistake Analysis'
authors: Kai Chen, Chunwei Wang, Kuo Yang, Jianhua Han, Lanqing Hong, Fei Mi, Hang Xu, Zhengying Liu, Wenyong Huang, Zhenguo Li, Dit-yan Yeung, Lifeng Shang, Xin Jiang, Qun Liu
conference: "Arxiv"
year: 2023
bibkey: chen2023gaining
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.10477'}
tags: ['Reinforcement Learning', 'RAG', 'Responsible AI', 'Tools']
---
The rapid development of large language models (LLMs) has not only provided
numerous opportunities but also presented significant challenges. This becomes
particularly evident when LLMs inadvertently generate harmful or toxic content,
either unintentionally or because of intentional inducement. Existing alignment
methods usually direct LLMs toward the favorable outcomes by utilizing
human-annotated, flawless instruction-response pairs. Conversely, this study
proposes a novel alignment technique based on mistake analysis, which
deliberately exposes LLMs to erroneous content to learn the reasons for
mistakes and how to avoid them. In this case, mistakes are repurposed into
valuable data for alignment, effectively helping to avoid the production of
erroneous responses. Without external models or human annotations, our method
leverages a model's intrinsic ability to discern undesirable mistakes and
improves the safety of its generated responses. Experimental results reveal
that our method outperforms existing alignment approaches in enhancing model
safety while maintaining the overall utility.
