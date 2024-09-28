---
layout: publication
title: keqing knowledge-based question answering is a nature chain-of-thought mentor of LLM
authors: Wang Chaojie, Xu Yishi, Peng Zhong, Zhang Chenxi, Chen Bo, Wang Xinrun, Feng Lei, An Bo
conference: "Arxiv"
year: 2023
bibkey: wang2023keqing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.00426"}
tags: ['ARXIV', 'Applications', 'LLM', 'Tools']
---
Large language models (LLMs) have exhibited remarkable performance on various natural language processing (NLP) tasks especially for question answering. However in the face of problems beyond the scope of knowledge these LLMs tend to talk nonsense with a straight face where the potential solution could be incorporating an Information Retrieval (IR) module and generating response based on these retrieved knowledge. In this paper we present a novel framework to assist LLMs such as ChatGPT to retrieve question-related structured information on the knowledge graph and demonstrate that Knowledge-based question answering (Keqing) could be a nature Chain-of-Thought (CoT) mentor to guide the LLM to sequentially find the answer entities of a complex question through interpretable logical chains. Specifically the workflow of Keqing will execute decomposing a complex question according to predefined templates retrieving candidate entities on knowledge graph reasoning answers of sub-questions and finally generating response with reasoning paths which greatly improves the reliability of LLMs response. The experimental results on KBQA datasets show that Keqing can achieve competitive performance and illustrate the logic of answering each question.
