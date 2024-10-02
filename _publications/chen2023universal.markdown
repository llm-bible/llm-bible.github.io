---
layout: publication
title: 'Universal Self-consistency For Large Language Model Generation'
authors: Chen Xinyun, Aksitov Renat, Alon Uri, Ren Jie, Xiao Kefan, Yin Pengcheng, Prakash Sushant, Sutton Charles, Wang Xuezhi, Zhou Denny
conference: "Arxiv"
year: 2023
bibkey: chen2023universal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.17311"}
tags: ['Applications', 'Prompting', 'RAG']
---
Self-consistency with chain-of-thought prompting (CoT) has demonstrated remarkable performance gains on various challenging tasks, by utilizing multiple reasoning paths sampled from large language models (LLMs). However, self-consistency relies on the answer extraction process to aggregate multiple solutions, which is not applicable to free-form answers. In this work, we propose Universal Self-Consistency (USC), which leverages LLMs themselves to select the most consistent answer among multiple candidates. We evaluate USC on a variety of benchmarks, including mathematical reasoning, code generation, long-context summarization, and open-ended question answering. On open-ended generation tasks where the original self-consistency method is not applicable, USC effectively utilizes multiple samples and improves the performance. For mathematical reasoning, USC matches the standard self-consistency performance without requiring the answer formats to be similar. Finally, without access to execution results, USC also matches the execution-based voting performance on code generation.
