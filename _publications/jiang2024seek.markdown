---
layout: publication
title: "Seek And Solve Reasoning For Table Question Answering"
authors: Jiang Ruya, Wang Chun, Deng Weihong
conference: "Arxiv"
year: 2024
bibkey: jiang2024seek
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.05286"}
tags: ['Applications', 'In Context Learning', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Table-based Question Answering (TQA) involves answering questions based on tabular data. The complexity of table structures and question logic makes this task difficult even for Large Language Models (LLMs). This paper improves TQA performance by leveraging LLMs reasoning capabilities. Inspired by how humans solve TQA tasks we propose a Seek-and-Solve pipeline that instructs the LLM to first seek relevant information and then answer questions. The two stages are integrated at the reasoning level and their Chain of Thought (CoT) paths are integrated into a coherent Seek-and-Solve CoT (SS-CoT). Furthermore we present a compact single-stage TQA-solving prompt distilled from the pipeline. Experiments demonstrate that under In-Context Learning settings using samples with SS-CoT paths as demonstrations the TQA-solving prompt can effectively guide the LLM to solve complex TQA tasks resulting in improved performance and reliability. Our results highlight the importance of properly eliciting LLMs reasoning capabilities in solving complex TQA tasks.
