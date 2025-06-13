---
layout: publication
title: 'Mramg-bench: A Comprehensive Benchmark For Advancing Multimodal Retrieval-augmented Multimodal Generation'
authors: Qinhan Yu, Zhiyou Xiao, Binghui Li, Zhengren Wang, Chong Chen, Wentao Zhang
conference: "Arxiv"
year: 2025
bibkey: yu2025mramg
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.04176'}
  - {name: "Code", url: 'https://github.com/MRAMG-Bench/MRAMG'}
tags: ['Attention Mechanism', 'Has Code', 'RAG', 'Model Architecture', 'Tools', 'Multimodal Models']
---
Recent advances in Retrieval-Augmented Generation (RAG) have significantly
improved response accuracy and relevance by incorporating external knowledge
into Large Language Models (LLMs). However, existing RAG methods primarily
focus on generating text-only answers, even in Multimodal Retrieval-Augmented
Generation (MRAG) scenarios, where multimodal elements are retrieved to assist
in generating text answers. To address this, we introduce the Multimodal
Retrieval-Augmented Multimodal Generation (MRAMG) task, in which we aim to
generate multimodal answers that combine both text and images, fully leveraging
the multimodal data within a corpus. Despite growing attention to this
challenging task, a notable lack of a comprehensive benchmark persists for
effectively evaluating its performance. To bridge this gap, we provide
MRAMG-Bench, a meticulously curated, human-annotated benchmark comprising 4,346
documents, 14,190 images, and 4,800 QA pairs, distributed across six distinct
datasets and spanning three domains: Web, Academia, and Lifestyle. The datasets
incorporate diverse difficulty levels and complex multi-image scenarios,
providing a robust foundation for evaluating the MRAMG task. To facilitate
rigorous evaluation, MRAMG-Bench incorporates a comprehensive suite of both
statistical and LLM-based metrics, enabling a thorough analysis of the
performance of generative models in the MRAMG task. Additionally, we propose an
efficient and flexible multimodal answer generation framework that can leverage
LLMs/MLLMs to generate multimodal responses. Our datasets and complete
evaluation results for 11 popular generative models are available at
https://github.com/MRAMG-Bench/MRAMG.
