---
layout: publication
title: 'An Entailment Tree Generation Approach For Multimodal Multi-hop Question Answering With Mixture-of-experts And Iterative Feedback Mechanism'
authors: Qing Zhang, Haocheng Lv, Jie Liu, Zhiyun Chen, Jianyong Duan, Hao Wang, Li He, Mingying Xv
conference: "MM 2024 Proceedings of the 32nd ACM International Conference on Multimedia Pages 4814 - 4822"
year: 2024
bibkey: zhang2024entailment
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.05821'}
tags: ['Interpretability and Explainability', 'Training Techniques', 'Applications', 'Tools', 'Multimodal Models']
---
With the rise of large-scale language models (LLMs), it is currently popular
and effective to convert multimodal information into text descriptions for
multimodal multi-hop question answering. However, we argue that the current
methods of multi-modal multi-hop question answering still mainly face two
challenges: 1) The retrieved evidence containing a large amount of redundant
information, inevitably leads to a significant drop in performance due to
irrelevant information misleading the prediction. 2) The reasoning process
without interpretable reasoning steps makes the model difficult to discover the
logical errors for handling complex questions. To solve these problems, we
propose a unified LLMs-based approach but without heavily relying on them due
to the LLM's potential errors, and innovatively treat multimodal multi-hop
question answering as a joint entailment tree generation and question answering
problem. Specifically, we design a multi-task learning framework with a focus
on facilitating common knowledge sharing across interpretability and prediction
tasks while preventing task-specific errors from interfering with each other
via mixture of experts. Afterward, we design an iterative feedback mechanism to
further enhance both tasks by feeding back the results of the joint training to
the LLM for regenerating entailment trees, aiming to iteratively refine the
potential answer. Notably, our method has won the first place in the official
leaderboard of WebQA (since April 10, 2024), and achieves competitive results
on MultimodalQA.
