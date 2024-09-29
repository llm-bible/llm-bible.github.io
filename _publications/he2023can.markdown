---
layout: publication
title: 'Can Large Language Models Understand Real-world Complex Instructions?'
authors: He Qianyu, Zeng Jie, Huang Wenhao, Chen Lina, Xiao Jin, He Qianxi, Zhou Xunzhe, Chen Lida, Wang Xintao, Huang Yuncheng, Ye Haoning, Li Zihan, Chen Shisong, Zhang Yikai, Gu Zhouhong, Liang Jiaqing, Xiao Yanghua
conference: "Arxiv"
year: 2023
bibkey: he2023can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.09150"}
  - {name: "Code", url: "https://github.com/Abbey4799/CELLO"}
tags: ['Applications', 'Ethics And Bias', 'Has Code', 'RAG', 'Reinforcement Learning']
---
Large language models (LLMs) can understand human instructions showing their potential for pragmatic applications beyond traditional NLP tasks. However they still struggle with complex instructions which can be either complex task descriptions that require multiple tasks and constraints or complex input that contains long context noise heterogeneous information and multi-turn format. Due to these features LLMs often ignore semantic constraints from task descriptions generate incorrect formats violate length or sample count constraints and be unfaithful to the input text. Existing benchmarks are insufficient to assess LLMs ability to understand complex instructions as they are close-ended and simple. To bridge this gap we propose CELLO a benchmark for evaluating LLMs ability to follow complex instructions systematically. We design eight features for complex instructions and construct a comprehensive evaluation dataset from real-world scenarios. We also establish four criteria and develop corresponding metrics as current ones are inadequate biased or too strict and coarse-grained. We compare the performance of representative Chinese-oriented and English-oriented models in following complex instructions through extensive experiments. Resources of CELLO are publicly available at https://github.com/Abbey4799/CELLO."
