---
layout: publication
title: DSGPT Domain45;specific Generative Pre45;training Of Transformers For Text Generation In E45;commerce Title And Review Summarization
authors: Zhang Xueying, Jiang Yunjiang, Shang Yue, Cheng Zhaomeng, Zhang Chi, Fan Xiaochuan, Xiao Yun, Long Bo
conference: "SIGIR"
year: 2021
bibkey: zhang2021domain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.08414"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Survey Paper', 'Training Techniques', 'Transformer']
---
We propose a novel domain45;specific generative pre45;training (DS45;GPT) method for text generation and apply it to the product titleand review summarization problems on E45;commerce mobile display.First we adopt a decoder45;only transformer architecture which fitswell for fine45;tuning tasks by combining input and output all to45;gether. Second we demonstrate utilizing only small amount of pre45;training data in related domains is powerful. Pre45;training a languagemodel from a general corpus such as Wikipedia or the CommonCrawl requires tremendous time and resource commitment andcan be wasteful if the downstream tasks are limited in variety. OurDSGPT is pre45;trained on a limited dataset the Chinese short textsummarization dataset (LCSTS). Third our model does not requireproduct45;related human45;labeled data. For title summarization taskthe state of art explicitly uses additional background knowledgein training and predicting stages. In contrast our model implic45;itly captures this knowledge and achieves significant improvementover other methods after fine45;tuning on the public Taobao.comdataset. For review summarization task we utilize JD.com in45;housedataset and observe similar improvement over standard machinetranslation methods which lack the flexibility of fine45;tuning. Ourproposed work can be simply extended to other domains for a widerange of text generation tasks.
