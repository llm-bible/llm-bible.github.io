---
layout: publication
title: Retrieve45;plan45;generation An Iterative Planning And Answering Framework For Knowledge45;intensive LLM Generation
authors: Lyu Yuanjie, Niu Zihan, Xie Zheyong, Zhang Chao, Xu Tong, Wang Yang, Chen Enhong
conference: "Arxiv"
year: 2024
bibkey: lyu2024retrieve
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14979"}
tags: ['Prompting', 'RAG', 'Tools']
---
Despite the significant progress of large language models (LLMs) in various tasks they often produce factual errors due to their limited internal knowledge. Retrieval45;Augmented Generation (RAG) which enhances LLMs with external knowledge sources offers a promising solution. However these methods can be misled by irrelevant paragraphs in retrieved documents. Due to the inherent uncertainty in LLM generation inputting the entire document may introduce off45;topic information causing the model to deviate from the central topic and affecting the relevance of the generated content. To address these issues we propose the Retrieve45;Plan45;Generation (RPG) framework. RPG generates plan tokens to guide subsequent generation in the plan stage. In the answer stage the model selects relevant fine45;grained paragraphs based on the plan and uses them for further answer generation. This plan45;answer process is repeated iteratively until completion enhancing generation relevance by focusing on specific topics. To implement this framework efficiently we utilize a simple but effective multi45;task prompt45;tuning method enabling the existing LLMs to handle both planning and answering. We comprehensively compare RPG with baselines across 5 knowledge45;intensive generation tasks demonstrating the effectiveness of our approach.
