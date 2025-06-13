---
layout: publication
title: 'Controlling Risk Of Retrieval-augmented Generation: A Counterfactual Prompting Framework'
authors: Lu Chen, Ruqing Zhang, Jiafeng Guo, Yixing Fan, Xueqi Cheng
conference: "Arxiv"
year: 2024
bibkey: chen2024controlling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.16146"}
  - {name: "Code", url: "https://github.com/ict-bigdatalab/RC-RAG"}
tags: ['Tools', 'Reinforcement Learning', 'RAG', 'Has Code', 'Prompting', 'Applications']
---
Retrieval-augmented generation (RAG) has emerged as a popular solution to
mitigate the hallucination issues of large language models. However, existing
studies on RAG seldom address the issue of predictive uncertainty, i.e., how
likely it is that a RAG model's prediction is incorrect, resulting in
uncontrollable risks in real-world applications. In this work, we emphasize the
importance of risk control, ensuring that RAG models proactively refuse to
answer questions with low confidence. Our research identifies two critical
latent factors affecting RAG's confidence in its predictions: the quality of
the retrieved results and the manner in which these results are utilized. To
guide RAG models in assessing their own confidence based on these two latent
factors, we develop a counterfactual prompting framework that induces the
models to alter these factors and analyzes the effect on their answers. We also
introduce a benchmarking procedure to collect answers with the option to
abstain, facilitating a series of experiments. For evaluation, we introduce
several risk-related metrics and the experimental results demonstrate the
effectiveness of our approach. Our code and benchmark dataset are available at
https://github.com/ict-bigdatalab/RC-RAG.
