---
layout: publication
title: SearchLVLMs A Plug-and-Play Framework for Augmenting Large Vision-Language Models by Searching Up-to-Date Internet Knowledge
authors: Li Chuanhao, Li Zhen, Jing Chenchen, Liu Shuo, Shao Wenqi, Wu Yuwei, Luo Ping, Qiao Yu, Zhang Kaipeng
conference: "Arxiv"
year: 2024
bibkey: li2024searchlvlms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14554"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Multimodal Models', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Large vision-language models (LVLMs) are ignorant of the up-to-date knowledge such as LLaVA series because they cannot be updated frequently due to the large amount of resources required and therefore fail in many cases. For example if a LVLM was released on January 2024 and it wouldnt know the singer of the theme song for the new Detective Conan movie which wasnt released until April 2024. To solve the problem a promising solution motivated by retrieval-augmented generation (RAG) is to provide LVLMs with up-to-date knowledge via internet search during inference i.e. internet-augmented generation (IAG) which is already integrated in some closed-source commercial LVLMs such as GPT-4V. However the specific mechanics underpinning them remain a mystery. In this paper we propose a plug-and-play framework for augmenting existing LVLMs in handling visual question answering (VQA) about up-to-date knowledge dubbed SearchLVLMs. A hierarchical filtering model is trained to effectively and efficiently find the most helpful content from the websites returned by a search engine to prompt LVLMs with up-to-date knowledge. To train the model and evaluate our frameworks performance we propose a pipeline to automatically generate news-related VQA samples to construct a dataset dubbed UDK-VQA. A multi-model voting mechanism is introduced to label the usefulness of website/content for VQA samples to construct the training set. Experimental results demonstrate the effectiveness of our framework outperforming GPT-4V by about 25 in accuracy.
