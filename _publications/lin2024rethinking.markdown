---
layout: publication
title: Rethinking Visual Prompting For Multimodal Large Language Models With External Knowledge
authors: Lin Yuanze, Li Yunsheng, Chen Dongdong, Xu Weijian, Clark Ronald, Torr Philip, Yuan Lu
conference: "Arxiv"
year: 2024
bibkey: lin2024rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.04681"}
tags: ['Multimodal Models', 'Prompting', 'RAG', 'Training Techniques']
---
In recent years multimodal large language models (MLLMs) have made significant strides by training on vast high45;quality image45;text datasets enabling them to generally understand images well. However the inherent difficulty in explicitly conveying fine45;grained or spatially dense information in text such as masks poses a challenge for MLLMs limiting their ability to answer questions requiring an understanding of detailed or localized visual elements. Drawing inspiration from the Retrieval45;Augmented Generation (RAG) concept this paper proposes a new visual prompt approach to integrate fine45;grained external knowledge gleaned from specialized vision models (e.g. instance segmentation/OCR models) into MLLMs. This is a promising yet underexplored direction for enhancing MLLMs performance. Our approach diverges from concurrent works which transform external knowledge into additional text prompts necessitating the model to indirectly learn the correspondence between visual content and text coordinates. Instead we propose embedding fine45;grained knowledge information directly into a spatial embedding map as a visual prompt. This design can be effortlessly incorporated into various MLLMs such as LLaVA and Mipha considerably improving their visual understanding performance. Through rigorous experiments we demonstrate that our method can enhance MLLM performance across nine benchmarks amplifying their fine45;grained context45;aware capabilities.
