---
layout: publication
title: Generative Multi45;modal Knowledge Retrieval With Large Language Models
authors: Long Xinwei, Zeng Jiali, Meng Fandong, Ma Zhiyuan, Zhang Kaiyan, Zhou Bowen, Zhou Jie
conference: "Arxiv"
year: 2024
bibkey: long2024generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.08206"}
tags: ['Applications', 'Efficiency And Optimization', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Knowledge retrieval with multi45;modal queries plays a crucial role in supporting knowledge45;intensive multi45;modal applications. However existing methods face challenges in terms of their effectiveness and training efficiency especially when it comes to training and integrating multiple retrievers to handle multi45;modal queries. In this paper we propose an innovative end45;to45;end generative framework for multi45;modal knowledge retrieval. Our framework takes advantage of the fact that large language models (LLMs) can effectively serve as virtual knowledge bases even when trained with limited data. We retrieve knowledge via a two45;step process 1) generating knowledge clues related to the queries and 2) obtaining the relevant document by searching databases using the knowledge clue. In particular we first introduce an object45;aware prefix45;tuning technique to guide multi45;grained visual learning. Then we align multi45;grained visual features into the textual feature space of the LLM employing the LLM to capture cross45;modal interactions. Subsequently we construct instruction data with a unified format for model training. Finally we propose the knowledge45;guided generation strategy to impose prior constraints in the decoding steps thereby promoting the generation of distinctive knowledge clues. Through experiments conducted on three benchmarks we demonstrate significant improvements ranging from 3.037; to 14.637; across all evaluation metrics when compared to strong baselines.
