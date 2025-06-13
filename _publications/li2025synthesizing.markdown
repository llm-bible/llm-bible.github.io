---
layout: publication
title: 'Omnisql: Synthesizing High-quality Text-to-sql Data At Scale'
authors: Haoyang Li, Shang Wu, Xiaokang Zhang, Xinmei Huang, Jing Zhang, Fuxin Jiang, Shuai Wang, Tieying Zhang, Jianjun Chen, Rui Shi, Hong Chen, Cuiping Li
conference: "Arxiv"
year: 2025
bibkey: li2025synthesizing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.02240'}
tags: ['RAG', 'Tools', 'Applications', 'Model Architecture', 'Fine-Tuning', 'Training Techniques', 'GPT', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Text-to-SQL, the task of translating natural language questions into SQL
queries, plays a crucial role in enabling non-experts to interact with
databases. While recent advancements in large language models (LLMs) have
significantly enhanced text-to-SQL performance, existing approaches face
notable limitations in real-world text-to-SQL applications. Prompting-based
methods often depend on closed-source LLMs, which are expensive, raise privacy
concerns, and lack customization. Fine-tuning-based methods, on the other hand,
suffer from poor generalizability due to the limited coverage of publicly
available training data. To overcome these challenges, we propose a novel and
scalable text-to-SQL data synthesis framework for automatically synthesizing
large-scale, high-quality, and diverse datasets without extensive human
intervention. Using this framework, we introduce SynSQL-2.5M, the first
million-scale text-to-SQL dataset, containing 2.5 million samples spanning over
16,000 synthetic databases. Each sample includes a database, SQL query, natural
language question, and chain-of-thought (CoT) solution. Leveraging SynSQL-2.5M,
we develop OmniSQL, a powerful open-source text-to-SQL model available in three
sizes: 7B, 14B, and 32B. Extensive evaluations across nine datasets demonstrate
that OmniSQL achieves state-of-the-art performance, matching or surpassing
leading closed-source and open-source LLMs, including GPT-4o and DeepSeek-V3,
despite its smaller size. We release all code, datasets, and models to support
further research.
