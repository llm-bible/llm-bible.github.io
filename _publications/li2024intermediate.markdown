---
layout: publication
title: Intermediate Distillation Data45;efficient Distillation From Black45;box Llms For Information Retrieval
authors: Li Zizhong, Zhang Haopeng, Zhang Jiawei
conference: "Arxiv"
year: 2024
bibkey: li2024intermediate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12169"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'RAG', 'Tools', 'Training Techniques']
---
Recent research has explored distilling knowledge from large language models (LLMs) to optimize retriever models especially within the retrieval45;augmented generation (RAG) framework. However most existing training methods rely on extracting supervision signals from LLMs weights or their output probabilities which is not only resource45;intensive but also incompatible with black45;box LLMs. In this paper we introduce textit123;Intermediate Distillation125; a data45;efficient knowledge distillation training scheme that treats LLMs as black boxes and distills their knowledge via an innovative LLM45;ranker45;retriever pipeline solely using LLMs ranking generation as the supervision signal. Extensive experiments demonstrate that our proposed method can significantly improve the performance of retriever models with only 1000 training instances. Moreover our distilled retriever model significantly boosts performance in question45;answering tasks within the RAG framework demonstrating the potential of LLMs to economically and effectively train smaller models.
