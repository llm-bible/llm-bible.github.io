---
layout: publication
title: 'R4: Reinforced Retriever-reorder-responder For Retrieval-augmented Large Language Models'
authors: Zhang Taolin, Li Dongyang, Chen Qizhou, Wang Chengyu, Huang Longtao, Xue Hui, He Xiaofeng, Huang Jun
conference: "Arxiv"
year: 2024
bibkey: zhang2024reinforced
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.02659"}
tags: ['Applications', 'Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security']
---
Retrieval-augmented large language models (LLMs) leverage relevant content retrieved by information retrieval systems to generate correct responses aiming to alleviate the hallucination problem. However existing retriever-responder methods typically append relevant documents to the prompt of LLMs to perform text generation tasks without considering the interaction of fine-grained structural semantics between the retrieved documents and the LLMs. This issue is particularly important for accurate response generation as LLMs tend to lose in the middle when dealing with input prompts augmented with lengthy documents. In this work we propose a new pipeline named Reinforced Retriever-Reorder-Responder (R^4) to learn document orderings for retrieval-augmented LLMs thereby further enhancing their generation abilities while the large numbers of parameters of LLMs remain frozen. The reordering learning process is divided into two steps according to the quality of the generated responses document order adjustment and document representation enhancement. Specifically document order adjustment aims to organize retrieved document orderings into beginning middle and end positions based on graph attention learning which maximizes the reinforced reward of response quality. Document representation enhancement further refines the representations of retrieved documents for responses of poor quality via document-level gradient adversarial learning. Extensive experiments demonstrate that our proposed pipeline achieves better factual question-answering performance on knowledge-intensive tasks compared to strong baselines across various public datasets. The source codes and trained models will be released upon paper acceptance.
