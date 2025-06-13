---
layout: publication
title: 'DSGPT: Domain-specific Generative Pre-training Of Transformers For Text Generation In E-commerce Title And Review Summarization'
authors: Xueying Zhang, Yunjiang Jiang, Yue Shang, Zhaomeng Cheng, Chi Zhang, Xiaochuan Fan, Yun Xiao, Bo Long
conference: "SIGIR 2021 Proceedings of the 44th International ACM SIGIR Conference on Research and Development in Information Retrieval July 2021 Pages 2146-2150"
year: 2021
bibkey: zhang2021domain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.08414"}
tags: ['Training Techniques', 'Model Architecture', 'Survey Paper', 'Language Modeling', 'GPT', 'Pretraining Methods', 'Transformer', 'Fine-Tuning', 'Pre-Training', 'Applications']
---
We propose a novel domain-specific generative pre-training (DS-GPT) method
for text generation and apply it to the product titleand review summarization
problems on E-commerce mobile display.First, we adopt a decoder-only
transformer architecture, which fitswell for fine-tuning tasks by combining
input and output all to-gether. Second, we demonstrate utilizing only small
amount of pre-training data in related domains is powerful. Pre-training a
languagemodel from a general corpus such as Wikipedia or the CommonCrawl
requires tremendous time and resource commitment, andcan be wasteful if the
downstream tasks are limited in variety. OurDSGPT is pre-trained on a limited
dataset, the Chinese short textsummarization dataset (LCSTS). Third, our model
does not requireproduct-related human-labeled data. For title summarization
task,the state of art explicitly uses additional background knowledgein
training and predicting stages. In contrast, our model implic-itly captures
this knowledge and achieves significant improvementover other methods, after
fine-tuning on the public Taobao.comdataset. For review summarization task, we
utilize JD.com in-housedataset, and observe similar improvement over standard
machinetranslation methods which lack the flexibility of fine-tuning.
Ourproposed work can be simply extended to other domains for a widerange of
text generation tasks.
