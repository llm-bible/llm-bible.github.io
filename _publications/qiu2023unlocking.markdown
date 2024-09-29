---
layout: publication
title: Unlocking Emergent Modularity In Large Language Models
authors: Qiu Zihan, Huang Zeyu, Fu Jie
conference: ""
year: 2023
bibkey: qiu2023unlocking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.10908"}
  - {name: "Code", url: "https://github.com/qiuzh20/EMoE"}
tags: ['Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Modular Neural Networks (MNNs) demonstrate various advantages over monolithic models. Existing MNNs are generally textit123;explicit125; their modular architectures are pre45;defined with individual modules expected to implement distinct functions. Recent works reveal that there exists textit123;implicit125; modularity in standard pre45;trained transformers namely textit123;Emergent Modularity125;. They indicate that such modular structures spontaneously exhibit during the early pre45;training phase. Despite the benefits of modularity most Language Models (LMs) are still treated as monolithic models in the pre45;train and fine45;tune paradigm with their emergent modularity locked and underutilized. In this work focusing on unlocking the emergent modularity in LMs we showcase that standard LMs could be fine45;tuned as their Mixture45;of45;Expert (MoEs) counterparts without introducing any extra parameters. Such MoEs are derived from emergent modularity and are referred to as Emergent MoEs (EMoE). Our experiments demonstrate that fine45;tuning EMoE effectively improves downstream in45;domain and out45;of45;domain generalization compared with vanilla fine45;tuning. Our analysis and ablation studies further illustrate that it is robust to various configurations and can scale up to Large Language Models (i.e. Llama245;7B and Llama45;30B). Code is available at https://github.com/qiuzh20/EMoE.
