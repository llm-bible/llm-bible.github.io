---
layout: publication
title: Unraveling Babel Exploring Multilingual Activation Patterns of LLMs and Their Applications
authors: Liu Weize, Xu Yinlong, Xu Hongxia, Chen Jintai, Hu Xuming, Wu Jian
conference: "Arxiv"
year: 2024
bibkey: liu2024unraveling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16367"}
tags: ['ARXIV', 'Applications', 'Efficiency And Optimization', 'LLM', 'NLP', 'RAG']
---
Recently large language models (LLMs) have achieved tremendous breakthroughs in the field of NLP but still lack understanding of their internal activities when processing different languages. We designed a method to convert dense LLMs into fine-grained MoE architectures and then visually studied the multilingual activation patterns of LLMs through expert activation frequency heatmaps. Through comprehensive experiments on different model families different model sizes and different variants we analyzed the distribution of high-frequency activated experts multilingual shared experts whether the activation patterns of different languages are related to language families and the impact of instruction tuning on activation patterns. We further explored leveraging the discovered differences in expert activation frequencies to guide unstructured pruning in two different ways. Experimental results demonstrated that our method significantly outperformed random expert pruning and even exceeded the performance of the original unpruned models in some languages. Additionally we found that configuring different pruning rates for different layers based on activation level differences could achieve better results. Our findings reveal the multilingual processing mechanisms within LLMs and utilize these insights to offer new perspectives for applications such as model pruning.
