---
layout: publication
title: 'Graph-constrained Reasoning: Faithful Reasoning On Knowledge Graphs With Large Language Models'
authors: Linhao Luo, Zicheng Zhao, Gholamreza Haffari, Yuan-fang Li, Chen Gong, Shirui Pan
conference: "Arxiv"
year: 2024
bibkey: luo2024graph
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13080"}
tags: ['Agentic', 'Tools', 'Applications', 'RAG', 'Training Techniques']
---
Large language models (LLMs) have demonstrated impressive reasoning abilities, but they still struggle with faithful reasoning due to knowledge gaps and hallucinations. To address these issues, knowledge graphs (KGs) have been utilized to enhance LLM reasoning through their structured knowledge. However, existing KG-enhanced methods, either retrieval-based or agent-based, encounter difficulties in accurately retrieving knowledge and efficiently traversing KGs at scale. In this work, we introduce graph-constrained reasoning (GCR), a novel framework that bridges structured knowledge in KGs with unstructured reasoning in LLMs. To eliminate hallucinations, GCR ensures faithful KG-grounded reasoning by integrating KG structure into the LLM decoding process through KG-Trie, a trie-based index that encodes KG reasoning paths. KG-Trie constrains the decoding process, allowing LLMs to directly reason on graphs and generate faithful reasoning paths grounded in KGs. Additionally, GCR leverages a lightweight KG-specialized LLM for graph-constrained reasoning alongside a powerful general LLM for inductive reasoning over multiple reasoning paths, resulting in accurate reasoning with zero reasoning hallucination. Extensive experiments on several KGQA benchmarks demonstrate that GCR achieves state-of-the-art performance and exhibits strong zero-shot generalizability to unseen KGs without additional training.
