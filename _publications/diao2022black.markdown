---
layout: publication
title: Black45;box Prompt Learning For Pre45;trained Language Models
authors: Diao Shizhe, Huang Zhichao, Xu Ruijia, Li Xuechun, Lin Yong, Zhou Xiao, Zhang Tong
conference: "Arxiv"
year: 2022
bibkey: diao2022black
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2201.08531"}
  - {name: "Code", url: "https://github.com/shizhediao/Black&#45;Box&#45;Prompt&#45;Learning"}
tags: ['BERT', 'Efficiency And Optimization', 'GPT', 'Has Code', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security', 'Tools', 'Training Techniques']
---
The increasing scale of general45;purpose Pre45;trained Language Models (PLMs) necessitates the study of more efficient adaptation across different downstream tasks. In this paper we establish a Black45;box Discrete Prompt Learning (BDPL) to resonate with pragmatic interactions between the cloud infrastructure and edge devices. Particularly instead of fine45;tuning the model in the cloud we adapt PLMs by prompt learning which efficiently optimizes only a few parameters of the discrete prompts. Moreover we consider the scenario that we do not have access to the parameters and gradients of the pre45;trained models except for its outputs given inputs. This black45;box setting secures the cloud infrastructure from potential attack and misuse to cause a single45;point failure which is preferable to the white45;box counterpart by current infrastructures. Under this black45;box constraint we apply a variance45;reduced policy gradient algorithm to estimate the gradients of parameters in the categorical distribution of each discrete prompt. In light of our method the user devices can efficiently tune their tasks by querying the PLMs bounded by a range of API calls. Our experiments on RoBERTa and GPT45;3 demonstrate that the proposed algorithm achieves significant improvement on eight benchmarks in a cloud45;device collaboration manner. Finally we conduct in45;depth case studies to comprehensively analyze our method in terms of various data sizes prompt lengths training budgets optimization objectives prompt transferability and explanations of the learned prompts. Our code will be available at https://github.com/shizhediao/Black&#45;Box&#45;Prompt&#45;Learning.
