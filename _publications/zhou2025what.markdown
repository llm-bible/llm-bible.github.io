---
layout: publication
title: 'What Are They Talking About? Benchmarking Large Language Models For Knowledge-grounded Discussion Summarization'
authors: Weixiao Zhou, Junnan Zhu, Gengyao Li, Xianfu Cheng, Xinnian Liang, Feifei Zhai, Zhoujun Li
conference: "Arxiv"
year: 2025
bibkey: zhou2025what
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.12474'}
tags: ['RAG', 'Tools', 'Applications', 'Merging', 'Prompting', 'Reinforcement Learning']
---
In this work, we investigate the performance of LLMs on a new task that requires combining discussion with background knowledge for summarization. This aims to address the limitation of outside observer confusion in existing dialogue summarization systems due to their reliance solely on discussion information. To achieve this, we model the task output as background and opinion summaries and define two standardized summarization patterns. To support assessment, we introduce the first benchmark comprising high-quality samples consistently annotated by human experts and propose a novel hierarchical evaluation framework with fine-grained, interpretable metrics. We evaluate 12 LLMs under structured-prompt and self-reflection paradigms. Our findings reveal: (1) LLMs struggle with background summary retrieval, generation, and opinion summary integration. (2) Even top LLMs achieve less than 69% average performance across both patterns. (3) Current LLMs lack adequate self-evaluation and self-correction capabilities for this task.
