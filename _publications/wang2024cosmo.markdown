---
layout: publication
title: COSMO COntrastive Streamlined MultimOdal Model with Interleaved Pre-Training
authors: Wang Alex Jinpeng, Li Linjie, Lin Kevin Qinghong, Wang Jianfeng, Lin Kevin, Yang Zhengyuan, Wang Lijuan, Shou Mike Zheng
conference: "Arxiv"
year: 2024
bibkey: wang2024cosmo
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.00849"}
tags: ['Applications', 'Few Shot', 'GPT', 'Language Modeling', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
In the evolution of Vision-Language Pre-training shifting from short-text comprehension to encompassing extended textual contexts is pivotal. Recent autoregressive vision-language models like leveraging the long-context capability of Large Language Models have excelled in few-shot text generation tasks but face challenges in alignment tasks. Addressing this gap we introduce the contrastive loss into text generation models presenting the COntrastive-Streamlined MultimOdal framework () strategically partitioning the language model into dedicated unimodal text processing and adept multimodal data handling components. our unified framework merges unimodal and multimodal elements enhancing model performance for tasks involving textual and visual data while notably reducing learnable parameters. However these models demand extensive long-text datasets yet the availability of high-quality long-text video datasets remains limited. To bridge this gap this work introduces an inaugural interleaved video-text dataset featuring comprehensive captions marking a significant step forward. Demonstrating its impact we illustrate how enhances model performance in image-text tasks. With 34 learnable parameters and utilizing 72 of the available data our model demonstrates significant superiority over OpenFlamingo~. For instance in the 4-shot flickr captioning task performance notably improves from 57.2 to 65.. The contributions of and are underscored by notable performance gains across 14 diverse downstream datasets encompassing both image-text and video-text tasks.
