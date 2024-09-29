---
layout: publication
title: Disperse45;then45;merge Pushing The Limits Of Instruction Tuning Via Alignment Tax Reduction
authors: Fu Tingchen, Cai Deng, Liu Lemao, Shi Shuming, Yan Rui
conference: "Arxiv"
year: 2024
bibkey: fu2024disperse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13432"}
tags: ['Ethics And Bias', 'Fine Tuning', 'Merging', 'Tools', 'Training Techniques']
---
Supervised fine45;tuning (SFT) on instruction45;following corpus is a crucial approach toward the alignment of large language models (LLMs). However the performance of LLMs on standard knowledge and reasoning benchmarks tends to suffer from deterioration at the latter stage of the SFT process echoing the phenomenon of alignment tax. Through our pilot study we put a hypothesis that the data biases are probably one cause behind the phenomenon. To address the issue we introduce a simple disperse45;then45;merge framework. To be concrete we disperse the instruction45;following data into portions and train multiple sub45;models using different data portions. Then we merge multiple models into a single one via model merging techniques. Despite its simplicity our framework outperforms various sophisticated methods such as data curation and training regularization on a series of standard knowledge and reasoning benchmarks.
