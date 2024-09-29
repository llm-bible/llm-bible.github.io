---
layout: publication
title: 'Compositional API Recommendation For Library-oriented Code Generation'
authors: Ma Zexiong, An Shengnan, Xie Bing, Lin Zeqi
conference: ""
year: 2024
bibkey: ma2024compositional
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.19431"}
tags: ['Applications', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Large language models (LLMs) have achieved exceptional performance in code generation. However the performance remains unsatisfactory in generating library-oriented code especially for the libraries not present in the training data of LLMs. Previous work utilizes API recommendation technology to help LLMs use libraries it retrieves APIs related to the user requirements then leverages them as context to prompt LLMs. However developmental requirements can be coarse-grained requiring a combination of multiple fine-grained APIs. This granularity inconsistency makes API recommendation a challenging task. To address this we propose CAPIR (Compositional API Recommendation) which adopts a divide-and-conquer strategy to recommend APIs for coarse-grained requirements. Specifically CAPIR employs an LLM-based Decomposer to break down a coarse-grained task description into several detailed subtasks. Then CAPIR applies an embedding-based Retriever to identify relevant APIs corresponding to each subtask. Moreover CAPIR leverages an LLM-based Reranker to filter out redundant APIs and provides the final recommendation. To facilitate the evaluation of API recommendation methods on coarse-grained requirements we present two challenging benchmarks RAPID (Recommend APIs based on Documentation) and LOCG (Library-Oriented Code Generation). Experimental results on these benchmarks demonstrate the effectiveness of CAPIR in comparison to existing baselines. Specifically on RAPIDs Torchdata-AR dataset compared to the state-of-the-art API recommendation approach CAPIR improves recall@5 from 18.737; to 43.237; and precision@5 from 15.537; to 37.137;. On LOCGs Torchdata-Code dataset compared to code generation without API recommendation CAPIR improves pass@100 from 16.037; to 28.037;.
