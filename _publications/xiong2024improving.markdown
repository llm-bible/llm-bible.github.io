---
layout: publication
title: 'Improving Retrieval-augmented Generation In Medicine With Iterative Follow-up Questions'
authors: Guangzhi Xiong, Qiao Jin, Xiao Wang, Minjia Zhang, Zhiyong Lu, Aidong Zhang
conference: "Arxiv"
year: 2024
bibkey: xiong2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.00727"}
  - {name: "Code", url: "https://github.com/Teddy-XiongGZ/MedRAG"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Prompting']
---
The emergent abilities of large language models (LLMs) have demonstrated
great potential in solving medical questions. They can possess considerable
medical knowledge, but may still hallucinate and are inflexible in the
knowledge updates. While Retrieval-Augmented Generation (RAG) has been proposed
to enhance the medical question-answering capabilities of LLMs with external
knowledge bases, it may still fail in complex cases where multiple rounds of
information-seeking are required. To address such an issue, we propose
iterative RAG for medicine (i-MedRAG), where LLMs can iteratively ask follow-up
queries based on previous information-seeking attempts. In each iteration of
i-MedRAG, the follow-up queries will be answered by a conventional RAG system
and they will be further used to guide the query generation in the next
iteration. Our experiments show the improved performance of various LLMs
brought by i-MedRAG compared with conventional RAG on complex questions from
clinical vignettes in the United States Medical Licensing Examination (USMLE),
as well as various knowledge tests in the Massive Multitask Language
Understanding (MMLU) dataset. Notably, our zero-shot i-MedRAG outperforms all
existing prompt engineering and fine-tuning methods on GPT-3.5, achieving an
accuracy of 69.68% on the MedQA dataset. In addition, we characterize the
scaling properties of i-MedRAG with different iterations of follow-up queries
and different numbers of queries per iteration. Our case studies show that
i-MedRAG can flexibly ask follow-up queries to form reasoning chains, providing
an in-depth analysis of medical questions. To the best of our knowledge, this
is the first-of-its-kind study on incorporating follow-up queries into medical
RAG. The implementation of i-MedRAG is available at
https://github.com/Teddy-XiongGZ/MedRAG.
