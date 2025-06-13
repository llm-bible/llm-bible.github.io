---
layout: publication
title: 'TROVE: A Challenge For Fine-grained Text Provenance Via Source Sentence Tracing And Relationship Classification'
authors: Junnan Zhu, Min Xiao, Yining Wang, Feifei Zhai, Yu Zhou, Chengqing Zong
conference: "Arxiv"
year: 2025
bibkey: zhu2025challenge
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.15289'}
  - {name: "Code", url: 'https://github.com/ZNLP/ZNLP-Dataset'}
tags: ['Has Code', 'Language Modeling', 'RAG', 'GPT', 'Applications', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Responsible AI']
---
LLMs have achieved remarkable fluency and coherence in text generation, yet their widespread adoption has raised concerns about content reliability and accountability. In high-stakes domains, it is crucial to understand where and how the content is created. To address this, we introduce the Text pROVEnance (TROVE) challenge, designed to trace each sentence of a target text back to specific source sentences within potentially lengthy or multi-document inputs. Beyond identifying sources, TROVE annotates the fine-grained relationships (quotation, compression, inference, and others), providing a deep understanding of how each target sentence is formed. To benchmark TROVE, we construct our dataset by leveraging three public datasets covering 11 diverse scenarios (e.g., QA and summarization) in English and Chinese, spanning source texts of varying lengths (0-5k, 5-10k, 10k+), emphasizing the multi-document and long-document settings essential for provenance. To ensure high-quality data, we employ a three-stage annotation process: sentence retrieval, GPT-4o provenance, and human provenance. We evaluate 11 LLMs under direct prompting and retrieval-augmented paradigms, revealing that retrieval is essential for robust performance, larger models perform better in complex relationship classification, and closed-source models often lead, yet open-source models show significant promise, particularly with retrieval augmentation. We make our dataset available here: https://github.com/ZNLP/ZNLP-Dataset.
