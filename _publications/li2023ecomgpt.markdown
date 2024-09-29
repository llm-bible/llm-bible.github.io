---
layout: publication
title: Ecomgpt Instruction-tuning Large Language Models With Chain-of-task Tasks For E-commerce
authors: Li Yangning, Ma Shirong, Wang Xiaobin, Huang Shen, Jiang Chengyue, Zheng Hai-tao, Xie Pengjun, Huang Fei, Jiang Yong
conference: "Arxiv"
year: 2023
bibkey: li2023ecomgpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.06966"}
tags: ['Ethics And Bias', 'Fine Tuning', 'GPT', 'Model Architecture', 'Training Techniques']
---
Recently instruction-following Large Language Models (LLMs) represented by ChatGPT have exhibited exceptional performance in general Natural Language Processing (NLP) tasks. However the unique characteristics of E-commerce data pose significant challenges to general LLMs. An LLM tailored specifically for E-commerce scenarios possessing robust cross-dataset/task generalization capabilities is a pressing necessity. To solve this issue in this work we proposed the first e-commerce instruction dataset EcomInstruct with a total of 2.5 million instruction data. EcomInstruct scales up the data size and task diversity by constructing atomic tasks with E-commerce basic data types such as product information user reviews. Atomic tasks are defined as intermediate tasks implicitly involved in solving a final task which we also call Chain-of-Task tasks. We developed EcomGPT with different parameter scales by training the backbone model BLOOMZ with the EcomInstruct. Benefiting from the fundamental semantic understanding capabilities acquired from the Chain-of-Task tasks EcomGPT exhibits excellent zero-shot generalization capabilities. Extensive experiments and human evaluations demonstrate that EcomGPT outperforms ChatGPT in term of cross-dataset/task generalization on E-commerce tasks.
