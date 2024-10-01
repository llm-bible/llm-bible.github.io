---
layout: publication
title: 'Retrieve-plan-generation: An Iterative Planning And Answering Framework For Knowledge-intensive LLM Generation'
authors: Lyu Yuanjie, Niu Zihan, Xie Zheyong, Zhang Chao, Xu Tong, Wang Yang, Chen Enhong
conference: "Arxiv"
year: 2024
bibkey: lyu2024retrieve
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14979"}
tags: ['Prompting', 'RAG', 'Tools']
---
Despite the significant progress of large language models (LLMs) in various tasks, they often produce factual errors due to their limited internal knowledge. Retrieval-Augmented Generation (RAG), which enhances LLMs with external knowledge sources, offers a promising solution. However, these methods can be misled by irrelevant paragraphs in retrieved documents. Due to the inherent uncertainty in LLM generation, inputting the entire document may introduce off-topic information, causing the model to deviate from the central topic and affecting the relevance of the generated content. To address these issues, we propose the Retrieve-Plan-Generation (RPG) framework. RPG generates plan tokens to guide subsequent generation in the plan stage. In the answer stage, the model selects relevant fine-grained paragraphs based on the plan and uses them for further answer generation. This plan-answer process is repeated iteratively until completion, enhancing generation relevance by focusing on specific topics. To implement this framework efficiently, we utilize a simple but effective multi-task prompt-tuning method, enabling the existing LLMs to handle both planning and answering. We comprehensively compare RPG with baselines across 5 knowledge-intensive generation tasks, demonstrating the effectiveness of our approach.
