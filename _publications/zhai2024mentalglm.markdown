---
layout: publication
title: 'Mentalglm Series: Explainable Large Language Models For Mental Health Analysis On Chinese Social Media'
authors: Wei Zhai, Nan Bai, Qing Zhao, Jianqiang Li, Fan Wang, Hongzhi Qi, Meng Jiang, Xiaoqin Wang, Bing Xiang Yang, Guanghui Fu
conference: "Arxiv"
year: 2024
bibkey: zhai2024mentalglm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10323"}
  - {name: "Code", url: "https://github.com/zwzzzQAQ/MentalGLM"}
tags: ['Interpretability and Explainability', 'Tools', 'Has Code', 'Prompting']
---
As the prevalence of mental health challenges, social media has emerged as a
key platform for individuals to express their emotions.Deep learning tends to
be a promising solution for analyzing mental health on social media. However,
black box models are often inflexible when switching between tasks, and their
results typically lack explanations. With the rise of large language models
(LLMs), their flexibility has introduced new approaches to the field. Also due
to the generative nature, they can be prompted to explain decision-making
processes. However, their performance on complex psychological analysis still
lags behind deep learning. In this paper, we introduce the first multi-task
Chinese Social Media Interpretable Mental Health Instructions (C-IMHI) dataset,
consisting of 9K samples, which has been quality-controlled and manually
validated. We also propose MentalGLM series models, the first open-source LLMs
designed for explainable mental health analysis targeting Chinese social media,
trained on a corpus of 50K instructions. The proposed models were evaluated on
three downstream tasks and achieved better or comparable performance compared
to deep learning models, generalized LLMs, and task fine-tuned LLMs. We
validated a portion of the generated decision explanations with experts,
showing promising results. We also evaluated the proposed models on a clinical
dataset, where they outperformed other LLMs, indicating their potential
applicability in the clinical field. Our models show strong performance,
validated across tasks and perspectives. The decision explanations enhance
usability and facilitate better understanding and practical application of the
models. Both the constructed dataset and the models are publicly available via:
https://github.com/zwzzzQAQ/MentalGLM.
