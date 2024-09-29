---
layout: publication
title: Llatrieval Llm-verified Retrieval For Verifiable Generation
authors: Li Xiaonan, Zhu Changtai, Li Linyang, Yin Zhangyue, Sun Tianxiang, Qiu Xipeng
conference: "Arxiv"
year: 2023
bibkey: li2023llatrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07838"}
tags: ['Applications', 'Reinforcement Learning']
---
Verifiable generation aims to let the large language model (LLM) generate text with supporting documents which enables the user to flexibly verify the answer and makes the LLMs output more reliable. Retrieval plays a crucial role in verifiable generation. Specifically the retrieved documents not only supplement knowledge to help the LLM generate correct answers but also serve as supporting evidence for the user to verify the LLMs output. However the widely used retrievers become the bottleneck of the entire pipeline and limit the overall performance. Their capabilities are usually inferior to LLMs since they often have much fewer parameters than the large language model and have not been demonstrated to scale well to the size of LLMs. If the retriever does not correctly find the supporting documents the LLM can not generate the correct and verifiable answer which overshadows the LLMs remarkable abilities. To address these limitations we propose LLatrieval (Large Language Model Verified Retrieval) where the LLM updates the retrieval result until it verifies that the retrieved documents can sufficiently support answering the question. Thus the LLM can iteratively provide feedback to retrieval and facilitate the retrieval result to fully support verifiable generation. Experiments show that LLatrieval significantly outperforms extensive baselines and achieves state-of-the-art results.
