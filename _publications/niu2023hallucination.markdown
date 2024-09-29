---
layout: publication
title: Ragtruth\: A Hallucination Corpus For Developing Trustworthy Retrieval-augmented Language Models
authors: Niu Cheng, Wu Yuanhao, Zhu Juno, Xu Siliang, Shum Kashun, Zhong Randy, Song Juntong, Zhang Tong
conference: "Arxiv"
year: 2023
bibkey: niu2023hallucination
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.00396"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Retrieval-augmented generation (RAG) has become a main technique for alleviating hallucinations in large language models (LLMs). Despite the integration of RAG LLMs may still present unsupported or contradictory claims to the retrieved contents. In order to develop effective hallucination prevention strategies under RAG it is important to create benchmark datasets that can measure the extent of hallucination. This paper presents RAGTruth a corpus tailored for analyzing word-level hallucinations in various domains and tasks within the standard RAG frameworks for LLM applications. RAGTruth comprises nearly 18000 naturally generated responses from diverse LLMs using RAG. These responses have undergone meticulous manual annotations at both the individual cases and word levels incorporating evaluations of hallucination intensity. We not only benchmark hallucination frequencies across different LLMs but also critically assess the effectiveness of several existing hallucination detection methodologies. Furthermore we show that using a high-quality dataset such as RAGTruth it is possible to finetune a relatively small LLM and achieve a competitive level of performance in hallucination detection when compared to the existing prompt-based approaches using state-of-the-art large language models such as GPT-4.
