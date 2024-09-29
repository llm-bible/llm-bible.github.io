---
layout: publication
title: 'On The Role Of Long-tail Knowledge In Retrieval Augmented Large Language Models'
authors: Li Dongyang, Yan Junbing, Zhang Taolin, Wang Chengyu, He Xiaofeng, Huang Longtao, Xue Hui, Huang Jun
conference: "Arxiv"
year: 2024
bibkey: li2024role
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16367"}
tags: ['Attention Mechanism', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Retrieval augmented generation (RAG) exhibits outstanding performance in promoting the knowledge capabilities of large language models (LLMs) with retrieved documents related to user queries. However RAG only focuses on improving the response quality of LLMs via enhancing queries indiscriminately with retrieved information paying little attention to what type of knowledge LLMs really need to answer original queries more accurately. In this paper we suggest that long-tail knowledge is crucial for RAG as LLMs have already remembered common world knowledge during large-scale pre-training. Based on our observation we propose a simple but effective long-tail knowledge detection method for LLMs. Specifically the novel Generative Expected Calibration Error (GECE) metric is derived to measure the long-tailness of knowledge based on both statistics and semantics. Hence we retrieve relevant documents and infuse them into the model for patching knowledge loopholes only when the input query relates to long-tail knowledge. Experiments show that compared to existing RAG pipelines our method achieves over 4x speedup in average inference time and consistent performance improvement in downstream tasks.
