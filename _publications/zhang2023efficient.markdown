---
layout: publication
title: Efficient Toxic Content Detection By Bootstrapping And Distilling Large Language Models
authors: Zhang Jiang, Wu Qiong, Xu Yiming, Cao Cheng, Du Zheng, Psounis Konstantinos
conference: "Arxiv"
year: 2023
bibkey: zhang2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.08303"}
tags: ['Applications', 'Pretraining Methods', 'Prompting']
---
Toxic content detection is crucial for online services to remove inappropriate content that violates community standards. To automate the detection process prior works have proposed varieties of machine learning (ML) approaches to train Language Models (LMs) for toxic content detection. However both their accuracy and transferability across datasets are limited. Recently Large Language Models (LLMs) have shown promise in toxic content detection due to their superior zero45;shot and few45;shot in45;context learning ability as well as broad transferability on ML tasks. However efficiently designing prompts for LLMs remains challenging. Moreover the high run45;time cost of LLMs may hinder their deployments in production. To address these challenges in this work we propose BD45;LLM a novel and efficient approach to Bootstrapping and Distilling LLMs for toxic content detection. Specifically we design a novel prompting method named Decision45;Tree45;of45;Thought (DToT) to bootstrap LLMs detection performance and extract high45;quality rationales. DToT can automatically select more fine45;grained context to re45;prompt LLMs when their responses lack confidence. Additionally we use the rationales extracted via DToT to fine45;tune student LMs. Our experimental results on various datasets demonstrate that DToT can improve the accuracy of LLMs by up to 4.637;. Furthermore student LMs fine45;tuned with rationales extracted via DToT outperform baselines on all datasets with up to 16.937; accuracy improvement while being more than 60x smaller than conventional LLMs. Finally we observe that student LMs fine45;tuned with rationales exhibit better cross45;dataset transferability.
