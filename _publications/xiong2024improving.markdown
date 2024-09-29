---
layout: publication
title: Improving Retrieval45;augmented Generation In Medicine With Iterative Follow45;up Questions
authors: Xiong Guangzhi, Jin Qiao, Wang Xiao, Zhang Minjia, Lu Zhiyong, Zhang Aidong
conference: "Arxiv"
year: 2024
bibkey: xiong2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.00727"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'RAG']
---
The emergent abilities of large language models (LLMs) have demonstrated great potential in solving medical questions. They can possess considerable medical knowledge but may still hallucinate and are inflexible in the knowledge updates. While Retrieval45;Augmented Generation (RAG) has been proposed to enhance the medical question45;answering capabilities of LLMs with external knowledge bases it may still fail in complex cases where multiple rounds of information45;seeking are required. To address such an issue we propose iterative RAG for medicine (i45;MedRAG) where LLMs can iteratively ask follow45;up queries based on previous information45;seeking attempts. In each iteration of i45;MedRAG the follow45;up queries will be answered by a conventional RAG system and they will be further used to guide the query generation in the next iteration. Our experiments show the improved performance of various LLMs brought by i45;MedRAG compared with conventional RAG on complex questions from clinical vignettes in the United States Medical Licensing Examination (USMLE) as well as various knowledge tests in the Massive Multitask Language Understanding (MMLU) dataset. Notably our zero45;shot i45;MedRAG outperforms all existing prompt engineering and fine45;tuning methods on GPT45;3.5 achieving an accuracy of 69.6837; on the MedQA dataset. In addition we characterize the scaling properties of i45;MedRAG with different iterations of follow45;up queries and different numbers of queries per iteration. Our case studies show that i45;MedRAG can flexibly ask follow45;up queries to form reasoning chains providing an in45;depth analysis of medical questions. To the best of our knowledge this is the first45;of45;its45;kind study on incorporating follow45;up queries into medical RAG.
