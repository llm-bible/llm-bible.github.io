---
layout: publication
title: PEARL Prompting Large Language Models To Plan And Execute Actions Over Long Documents
authors: Sun Simeng, Liu Yang, Wang Shuohang, Zhu Chenguang, Iyyer Mohit
conference: "Arxiv"
year: 2023
bibkey: sun2023prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14564"}
tags: ['Few Shot', 'GPT', 'In Context Learning', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Strategies such as chain-of-thought prompting improve the performance of large language models (LLMs) on complex reasoning tasks by decomposing input examples into intermediate steps. However it remains unclear how to apply such methods to reason over long input documents in which both the decomposition and the output of each intermediate step are non-trivial to obtain. In this work we propose PEARL a prompting framework to improve reasoning over long documents which consists of three stages action mining plan formulation and plan execution. More specifically given a question about a long document PEARL decomposes the question into a sequence of actions (e.g. SUMMARIZE FIND_EVENT FIND_RELATION) and then executes them over the document to obtain the answer. Each stage of PEARL is implemented via zero-shot or few-shot prompting of LLMs (in our work GPT-4) with minimal human input. We evaluate PEARL on a challenging subset of the QuALITY dataset which contains questions that require complex reasoning over long narrative texts. PEARL outperforms zero-shot and chain-of-thought prompting on this dataset and ablation experiments show that each stage of PEARL is critical to its performance. Overall PEARL is a first step towards leveraging LLMs to reason over long documents.
