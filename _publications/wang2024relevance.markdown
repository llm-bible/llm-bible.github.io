---
layout: publication
title: REAR A Relevance-aware Retrieval-augmented Framework For Open-domain Question Answering
authors: Wang Yuhao, Ren Ruiyang, Li Junyi, Zhao Wayne Xin, Liu Jing, Wen Ji-rong
conference: "Arxiv"
year: 2024
bibkey: wang2024relevance
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17497"}
  - {name: "Code", url: "https://github.com/RUCAIBox/REAR"}
tags: ['Applications', 'Has Code', 'Merging', 'Model Architecture', 'RAG', 'Tools', 'Training Techniques']
---
Considering the limited internal parametric knowledge retrieval-augmented generation (RAG) has been widely used to extend the knowledge scope of large language models (LLMs). Despite the extensive efforts on RAG research in existing methods LLMs cannot precisely assess the relevance of retrieved documents thus likely leading to misleading or even incorrect utilization of external knowledge (i.e. retrieved documents). To address this issue in this paper we propose REAR a RElevance-Aware Retrieval-augmented approach for open-domain question answering (QA). As the key motivation we aim to enhance the self-awareness of source relevance for LLMs so as to adaptively utilize external knowledge in RAG systems. Specially we develop a new architecture for LLM based RAG system by incorporating a specially designed rank head that precisely assesses the relevance of retrieved documents. Furthermore we propose an improved training method based on bi-granularity relevance fusion and noise-resistant training. By combining the improvements in both architecture and training our proposed REAR can better utilize external knowledge by effectively perceiving the relevance of retrieved documents. Experiments on four open-domain QA tasks show that REAR significantly outperforms previous a number of competitive RAG approaches. Our code and data can be accessed at https://github.com/RUCAIBox/REAR."
