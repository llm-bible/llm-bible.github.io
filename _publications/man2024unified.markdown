---
layout: publication
title: ULLME A Unified Framework For Large Language Model Embeddings With Generation45;augmented Learning
authors: Man Hieu, Ngo Nghia Trung, Dernoncourt Franck, Nguyen Thien Huu
conference: "Arxiv"
year: 2024
bibkey: man2024unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03402"}
  - {name: "Code", url: "https://github.com/nlp&#45;uoregon/ullme"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Large Language Models (LLMs) excel in various natural language processing tasks but leveraging them for dense passage embedding remains challenging. This is due to their causal attention mechanism and the misalignment between their pre45;training objectives and the text ranking tasks. Despite some recent efforts to address these issues existing frameworks for LLM45;based text embeddings have been limited by their support for only a limited range of LLM architectures and fine45;tuning strategies limiting their practical application and versatility. In this work we introduce the Unified framework for Large Language Model Embedding (ULLME) a flexible plug45;and45;play implementation that enables bidirectional attention across various LLMs and supports a range of fine45;tuning strategies. We also propose Generation45;augmented Representation Learning (GRL) a novel fine45;tuning method to boost LLMs for text embedding tasks. GRL enforces consistency between representation45;based and generation45;based relevance scores leveraging LLMs powerful generative abilities for learning passage embeddings. To showcase our frameworks flexibility and effectiveness we release three pre45;trained models from ULLME with different backbone architectures ranging from 1.5B to 8B parameters all of which demonstrate strong performance on the Massive Text Embedding Benchmark. Our framework is publicly available at https://github.com/nlp&#45;uoregon/ullme. A demo video for ULLME can also be found at https://rb.gy/ws1ile.
