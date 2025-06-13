---
layout: publication
title: 'MIRAGE: A Metric-intensive Benchmark For Retrieval-augmented Generation Evaluation'
authors: Chanhee Park, Hyeonseok Moon, Chanjun Park, Heuiseok Lim
conference: "Arxiv"
year: 2025
bibkey: park2025metric
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.17137"}
  - {name: "Code", url: "https://github.com/nlpai-lab/MIRAGE"}
tags: ['Security', 'Applications', 'Has Code', 'RAG']
---
Retrieval-Augmented Generation (RAG) has gained prominence as an effective
method for enhancing the generative capabilities of Large Language Models
(LLMs) through the incorporation of external knowledge. However, the evaluation
of RAG systems remains a challenge, due to the intricate interplay between
retrieval and generation components. This limitation has resulted in a scarcity
of benchmarks that facilitate a detailed, component-specific assessment. In
this work, we present MIRAGE, a Question Answering dataset specifically
designed for RAG evaluation. MIRAGE consists of 7,560 curated instances mapped
to a retrieval pool of 37,800 entries, enabling an efficient and precise
evaluation of both retrieval and generation tasks. We also introduce novel
evaluation metrics aimed at measuring RAG adaptability, encompassing dimensions
such as noise vulnerability, context acceptability, context insensitivity, and
context misinterpretation. Through comprehensive experiments across various
retriever-LLM configurations, we provide new insights into the optimal
alignment of model pairs and the nuanced dynamics within RAG systems. The
dataset and evaluation code are publicly available, allowing for seamless
integration and customization in diverse research settings\footnote\{The MIRAGE
code and data are available at https://github.com/nlpai-lab/MIRAGE.
