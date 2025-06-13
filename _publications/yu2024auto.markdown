---
layout: publication
title: 'Auto-rag: Autonomous Retrieval-augmented Generation For Large Language Models'
authors: Tian Yu, Shaolei Zhang, Yang Feng
conference: "Arxiv"
year: 2024
bibkey: yu2024auto
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.19443"}
  - {name: "Code", url: "https://github.com/ictnlp/Auto-RAG"}
tags: ['Few-Shot', 'Reinforcement Learning', 'RAG', 'Has Code', 'Interpretability and Explainability', 'Prompting', 'In-Context Learning']
---
Iterative retrieval refers to the process in which the model continuously
queries the retriever during generation to enhance the relevance of the
retrieved knowledge, thereby improving the performance of Retrieval-Augmented
Generation (RAG). Existing work typically employs few-shot prompting or
manually constructed rules to implement iterative retrieval. This introduces
additional inference overhead and overlooks the remarkable reasoning
capabilities of Large Language Models (LLMs). In this paper, we introduce
Auto-RAG, an autonomous iterative retrieval model centered on the LLM's
powerful decision-making capabilities. Auto-RAG engages in multi-turn dialogues
with the retriever, systematically planning retrievals and refining queries to
acquire valuable knowledge. This process continues until sufficient external
information is gathered, at which point the results are presented to the user.
To this end, we develop a method for autonomously synthesizing reasoning-based
decision-making instructions in iterative retrieval and fine-tuned the latest
open-source LLMs. The experimental results indicate that Auto-RAG is capable of
autonomous iterative interaction with the retriever, effectively leveraging the
remarkable reasoning and decision-making abilities of LLMs, which lead to
outstanding performance across six benchmarks. Further analysis reveals that
Auto-RAG can autonomously adjust the number of iterations based on the
difficulty of the questions and the utility of the retrieved knowledge, without
requiring any human intervention. Moreover, Auto-RAG expresses the iterative
retrieval process in natural language, enhancing interpretability while
providing users with a more intuitive experience\footnote\{Code is available at
\url\{https://github.com/ictnlp/Auto-RAG\}.
