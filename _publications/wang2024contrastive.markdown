---
layout: publication
title: COSMO Contrastive Streamlined Multimodal Model With Interleaved Pre-training
authors: Wang Alex Jinpeng, Li Linjie, Lin Kevin Qinghong, Wang Jianfeng, Lin Kevin, Yang Zhengyuan, Wang Lijuan, Shou Mike Zheng
conference: "Arxiv"
year: 2024
bibkey: wang2024contrastive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.00849"}
tags: ['Applications', 'Few Shot', 'GPT', 'Language Modeling', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
In the evolution of Vision-Language Pre-training shifting from short-text comprehension to encompassing extended textual contexts is pivotal. Recent autoregressive vision-language models like (cite)flamingo palme leveraging the long-context capability of Large Language Models have excelled in few-shot text generation tasks but face challenges in alignment tasks. Addressing this gap we introduce the contrastive loss into text generation models presenting the COntrastive-Streamlined MultimOdal framework ((ModelName)) strategically partitioning the language model into dedicated unimodal text processing and adept multimodal data handling components. (ModelName) our unified framework merges unimodal and multimodal elements enhancing model performance for tasks involving textual and visual data while notably reducing learnable parameters. However these models demand extensive long-text datasets yet the availability of high-quality long-text video datasets remains limited. To bridge this gap this work introduces (VideoDatasetName) an inaugural interleaved video-text dataset featuring comprehensive captions marking a significant step forward. Demonstrating its impact we illustrate how (VideoDatasetName) enhances model performance in image-text tasks. With 3437; learnable parameters and utilizing 7237; of the available data our model demonstrates significant superiority over OpenFlamingo~(citeopenflamingo). For instance in the 4-shot flickr captioning task performance notably improves from 57.237; to 65.37;. The contributions of (ModelName) and (VideoDatasetName) are underscored by notable performance gains across 14 diverse downstream datasets encompassing both image-text and video-text tasks.
