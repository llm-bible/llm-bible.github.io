---
layout: publication
title: Limited Out45;of45;context Knowledge Reasoning In Large Language Models
authors: Hu Peng, Gao Changjiang, Gao Ruiqi, Chen Jiajun, Huang Shujian
conference: "Arxiv"
year: 2024
bibkey: hu2024limited
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07393"}
  - {name: "Code", url: "https://github.com/NJUNLP/ID&#45;OCKR"}
tags: ['Has Code', 'Prompting', 'RAG', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated strong capabilities as knowledge bases and significant in45;context reasoning capabilities. However previous work challenges their out45;of45;context reasoning ability i.e. the ability to infer information from their training data instead of from the context or prompt. This paper focuses on a significant facet of out45;of45;context reasoning Out45;of45;Context Knowledge Reasoning (OCKR) which is to combine multiple knowledge to infer new knowledge. We designed a synthetic dataset with seven representative OCKR tasks to systematically assess the OCKR capabilities of LLMs. Using this dataset we evaluated the LLaMA245;13B45;chat model and discovered that its proficiency in this aspect is limited regardless of whether the knowledge is trained in a separate or adjacent training settings. Moreover training the model to reason with complete reasoning data did not result in significant improvement. Training the model to perform explicit knowledge retrieval helps in only one of the tasks indicating that the models limited OCKR capabilities are due to difficulties in retrieving relevant knowledge. Furthermore we treat cross45;lingual knowledge transfer as a distinct form of OCKR and evaluate this ability. Our results show that the evaluated model also exhibits limited ability in transferring knowledge across languages. The dataset used in this study is available at https://github.com/NJUNLP/ID&#45;OCKR.
