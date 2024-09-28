---
layout: publication
title: Rescue Ranking LLM Responses with Partial Ordering to Improve Response Generation
authors: Wang Yikun, Zheng Rui, Li Haoming, Zhang Qi, Gui Tao, Liu Fei
conference: "Arxiv"
year: 2023
bibkey: wang2023rescue
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09136"}
tags: ['ARXIV', 'Fine Tuning', 'Pretraining Methods', 'Supervised', 'Tools']
---
Customizing LLMs for a specific task involves separating high-quality responses from lower-quality ones. This skill can be developed using supervised fine-tuning with extensive human preference data. However obtaining a large volume of expert-annotated data is costly for most tasks. In this paper we explore a novel method to optimize LLMs using ranking metrics. This method trains the model to prioritize the best responses from a pool of candidates created for a particular task. Rather than a traditional full ordering we advocate for a partial ordering as achieving consensus on the perfect order of candidate responses can be challenging. Our partial ordering is more robust less sensitive to noise and can be achieved with limited human annotations or through heuristic methods. We test our systems improved response generation ability using benchmark datasets including textual entailment and multi-document question answering. We conduct ablation studies to understand crucial factors such as how to gather candidate responses for a specific task determine their most suitable order and balance supervised fine-tuning with ranking metrics. Our approach named Rescue offers a promising avenue for enhancing the response generation and task accuracy of LLMs.
