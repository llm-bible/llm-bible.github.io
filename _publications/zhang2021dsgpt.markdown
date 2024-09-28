---
layout: publication
title: DSGPT Domain-Specific Generative Pre-Training of Transformers for Text Generation in E-commerce Title and Review Summarization
authors: Zhang Xueying, Jiang Yunjiang, Shang Yue, Cheng Zhaomeng, Zhang Chi, Fan Xiaochuan, Xiao Yun, Long Bo
conference: "SIGIR"
year: 2021
bibkey: zhang2021dsgpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.08414"}
tags: ['Fine Tuning', 'GPT', 'Language Modeling', 'PRE Training', 'Survey Paper', 'Training Techniques', 'Transformer']
---
We propose a novel domain-specific generative pre-training (DS-GPT) method for text generation and apply it to the product titleand review summarization problems on E-commerce mobile display.First we adopt a decoder-only transformer architecture which fitswell for fine-tuning tasks by combining input and output all to-gether. Second we demonstrate utilizing only small amount of pre-training data in related domains is powerful. Pre-training a languagemodel from a general corpus such as Wikipedia or the CommonCrawl requires tremendous time and resource commitment andcan be wasteful if the downstream tasks are limited in variety. OurDSGPT is pre-trained on a limited dataset the Chinese short textsummarization dataset (LCSTS). Third our model does not requireproduct-related human-labeled data. For title summarization taskthe state of art explicitly uses additional background knowledgein training and predicting stages. In contrast our model implic-itly captures this knowledge and achieves significant improvementover other methods after fine-tuning on the public Taobao.comdataset. For review summarization task we utilize JD.com in-housedataset and observe similar improvement over standard machinetranslation methods which lack the flexibility of fine-tuning. Ourproposed work can be simply extended to other domains for a widerange of text generation tasks.
