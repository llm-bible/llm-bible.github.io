---
layout: publication
title: Bwarea Model Learning World Model Inverse Dynamics And Policy For Controllable Language Generation
authors: Jia Chengxing, Wang Pengyuan, Li Ziniu, Li Yi-chen, Zhang Zhilong, Tang Nan, Yu Yang
conference: "Arxiv"
year: 2024
bibkey: jia2024bwarea
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17039"}
tags: ['Applications', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) have catalyzed a paradigm shift in natural language processing yet their limited controllability poses a significant challenge for downstream applications. We aim to address this by drawing inspiration from the neural mechanisms of the human brain specifically Brocas and Wernickes areas which are crucial for language generation and comprehension respectively. In particular Brocas area receives cognitive decision signals from Wernickes area treating the language generation as an intricate decision45;making process which differs from the fully auto45;regressive language generation of existing LLMs. In a similar vein our proposed system the BWArea model conceptualizes language generation as a decision45;making task. This model has three components a language world model an inverse dynamics model and a cognitive policy. Like Wernickes area the inverse dynamics model is designed to deduce the underlying cognitive intentions or latent actions behind each token. The BWArea model is amenable to both pre45;training and fine45;tuning like existing LLMs. With 30B clean pre45;training tokens we have trained a BWArea model which achieves competitive performance with LLMs of equal size (1B parameters). Unlike fully auto45;regressive LLMs its pre45;training performance does not degenerate if dirty data unintentionally appears. This shows the advantage of a decomposed structure of BWArea model in reducing efforts in laborious data selection and labeling. Finally we reveal that the BWArea model offers enhanced controllability via fine45;tuning the cognitive policy with downstream reward metrics thereby facilitating alignment with greater simplicity. On 9 out of 10 tasks from two suites TextWorld and BigBench Hard our method shows superior performance to auto45;regressive LLMs.
