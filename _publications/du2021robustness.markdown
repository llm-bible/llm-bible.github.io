---
layout: publication
title: 'Robustness Challenges In Model Distillation And Pruning For Natural Language Understanding'
authors: Du Mengnan, Mukherjee Subhabrata, Cheng Yu, Shokouhi Milad, Hu Xia, Awadallah Ahmed Hassan
conference: "Arxiv"
year: 2021
bibkey: du2021robustness
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.08419"}
tags: ['Applications', 'BERT', 'Bias Mitigation', 'Distillation', 'Efficiency And Optimization', 'Ethics And Bias', 'Model Architecture', 'Pruning', 'Quantization', 'RAG', 'Reinforcement Learning', 'Security', 'Tools']
---
Recent work has focused on compressing pre-trained language models (PLMs) like BERT where the major focus has been to improve the in-distribution performance for downstream tasks. However, very few of these studies have analyzed the impact of compression on the generalizability and robustness of compressed models for out-of-distribution (OOD) data. Towards this end, we study two popular model compression techniques including knowledge distillation and pruning and show that the compressed models are significantly less robust than their PLM counterparts on OOD test sets although they obtain similar performance on in-distribution development sets for a task. Further analysis indicates that the compressed models overfit on the shortcut samples and generalize poorly on the hard ones. We further leverage this observation to develop a regularization strategy for robust model compression based on sample uncertainty. Experimental results on several natural language understanding tasks demonstrate that our bias mitigation framework improves the OOD generalization of the compressed models, while not sacrificing the in-distribution task performance.
