---
layout: publication
title: 'Black-box Prompt Learning For Pre-trained Language Models'
authors: Shizhe Diao, Zhichao Huang, Ruijia Xu, Xuechun Li, Yong Lin, Xiao Zhou, Tong Zhang
conference: "Arxiv"
year: 2022
bibkey: diao2022black
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2201.08531'}
  - {name: "Code", url: 'https://github.com/shizhediao/Black-Box-Prompt-Learning'}
tags: ['Has Code', 'Interpretability and Explainability', 'RAG', 'Efficiency and Optimization', 'Security', 'Tools', 'Model Architecture', 'Training Techniques', 'Fine-Tuning', 'BERT', 'GPT', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
The increasing scale of general-purpose Pre-trained Language Models (PLMs)
necessitates the study of more efficient adaptation across different downstream
tasks. In this paper, we establish a Black-box Discrete Prompt Learning (BDPL)
to resonate with pragmatic interactions between the cloud infrastructure and
edge devices. Particularly, instead of fine-tuning the model in the cloud, we
adapt PLMs by prompt learning, which efficiently optimizes only a few
parameters of the discrete prompts. Moreover, we consider the scenario that we
do not have access to the parameters and gradients of the pre-trained models,
except for its outputs given inputs. This black-box setting secures the cloud
infrastructure from potential attack and misuse to cause a single-point
failure, which is preferable to the white-box counterpart by current
infrastructures. Under this black-box constraint, we apply a variance-reduced
policy gradient algorithm to estimate the gradients of parameters in the
categorical distribution of each discrete prompt. In light of our method, the
user devices can efficiently tune their tasks by querying the PLMs bounded by a
range of API calls. Our experiments on RoBERTa and GPT-3 demonstrate that the
proposed algorithm achieves significant improvement on eight benchmarks in a
cloud-device collaboration manner. Finally, we conduct in-depth case studies to
comprehensively analyze our method in terms of various data sizes, prompt
lengths, training budgets, optimization objectives, prompt transferability, and
explanations of the learned prompts. Our code will be available at
https://github.com/shizhediao/Black-Box-Prompt-Learning.
