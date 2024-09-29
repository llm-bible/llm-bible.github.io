---
layout: publication
title: Mindstar Enhancing Math Reasoning In Pre45;trained Llms At Inference Time
authors: Kang Jikun, Li Xin Zhe, Chen Xi, Kazemi Amirreza, Sun Qianyi, Chen Boxing, Li Dong, He Xu, He Quan, Wen Feng, Hao Jianye, Yao Jun
conference: "Arxiv"
year: 2024
bibkey: kang2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16265"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools']
---
Although Large Language Models (LLMs) achieve remarkable performance across various tasks they often struggle with complex reasoning tasks such as answering mathematical questions. Recent efforts to address this issue have primarily focused on leveraging mathematical datasets through supervised fine45;tuning or self45;improvement techniques. However these methods often depend on high45;quality datasets that are difficult to prepare or they require substantial computational resources for fine45;tuning. Inspired by findings that LLMs know how to produce the right answer but struggle to select the correct reasoning path we propose a purely inference45;based searching method 45;45; MindStar (M). This method formulates reasoning tasks as searching problems and proposes two search ideas to identify the optimal reasoning paths. We evaluate the M framework on both the GSM8K and MATH datasets comparing its performance with existing open and closed45;source LLMs. Our results demonstrate that M significantly enhances the reasoning abilities of open45;source models such as Llama45;245;13B and Mistral45;7B and achieves comparable performance to GPT45;3.5 and Grok45;1 but with substantially reduced model size and computational costs.
