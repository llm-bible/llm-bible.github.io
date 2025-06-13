---
layout: publication
title: 'Chemdfm: A Large Language Foundation Model For Chemistry'
authors: Zihan Zhao, Da Ma, Lu Chen, Liangtai Sun, Zihao Li, Yi Xia, Bo Chen, Hongshen Xu, Zichen Zhu, Su Zhu, Shuai Fan, Guodong Shen, Kai Yu, Xin Chen
conference: "Arxiv"
year: 2024
bibkey: zhao2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.14818"}
  - {name: "Code", url: "https://huggingface.co/OpenDFM/ChemDFM-v1.0-13B)"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'GPT', 'Has Code']
---
Artificial intelligence (AI) has played an increasingly important role in
chemical research. However, most models currently used in chemistry are
specialist models that require training and tuning for specific tasks. A more
generic and efficient solution would be an AI model that could address many
tasks and support free-form dialogue in the broad field of chemistry. In its
utmost form, such a generalist AI chemist could be referred to as Chemical
General Intelligence. Large language models (LLMs) have recently logged
tremendous success in the general domain of natural language processing,
showing emerging task generalization and free-form dialogue capabilities.
However, domain knowledge of chemistry is largely missing when training
general-domain LLMs. The lack of such knowledge greatly hinders the performance
of generalist LLMs in the field of chemistry. To this end, we develop ChemDFM,
a pioneering LLM for chemistry trained on 34B tokens from chemical literature
and textbooks, and fine-tuned using 2.7M instructions. As a result, it can
understand and reason with chemical knowledge in free-form dialogue.
Quantitative evaluations show that ChemDFM significantly surpasses most
representative open-source LLMs. It outperforms GPT-4 on a great portion of
chemical tasks, despite the substantial size difference. We have open-sourced
the inference codes, evaluation datasets, and model weights of ChemDFM on
Huggingface (https://huggingface.co/OpenDFM/ChemDFM-v1.0-13B).
