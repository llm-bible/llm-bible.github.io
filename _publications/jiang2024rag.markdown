---
layout: publication
title: 'Rag-star: Enhancing Deliberative Reasoning With Retrieval Augmented Verification And Refinement'
authors: Jinhao Jiang, Jiayi Chen, Junyi Li, Ruiyang Ren, Shijie Wang, Wayne Xin Zhao, Yang Song, Tao Zhang
conference: "Arxiv"
year: 2024
bibkey: jiang2024rag
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.12881'}
tags: ['Reinforcement Learning', 'RAG', 'GPT', 'Model Architecture']
---
Existing large language models (LLMs) show exceptional problem-solving
capabilities but might struggle with complex reasoning tasks. Despite the
successes of chain-of-thought and tree-based search methods, they mainly depend
on the internal knowledge of LLMs to search over intermediate reasoning steps,
limited to dealing with simple tasks involving fewer reasoning steps. In this
paper, we propose \textbf\{RAG-Star\}, a novel RAG approach that integrates the
retrieved information to guide the tree-based deliberative reasoning process
that relies on the inherent knowledge of LLMs. By leveraging Monte Carlo Tree
Search, RAG-Star iteratively plans intermediate sub-queries and answers for
reasoning based on the LLM itself. To consolidate internal and external
knowledge, we propose an retrieval-augmented verification that utilizes query-
and answer-aware reward modeling to provide feedback for the inherent reasoning
of LLMs. Our experiments involving Llama-3.1-8B-Instruct and GPT-4o demonstrate
that RAG-Star significantly outperforms previous RAG and reasoning methods.
