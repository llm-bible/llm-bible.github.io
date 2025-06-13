---
layout: publication
title: 'Markov Chain Of Thought For Efficient Mathematical Reasoning'
authors: Wen Yang, Minpeng Liao, Kai Fan
conference: "Arxiv"
year: 2024
bibkey: yang2024markov
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.17635'}
  - {name: "Code", url: 'https://github.com/james-yw/Markov-Chain-of-Thought'}
tags: ['Has Code', 'Efficiency and Optimization']
---
Chain of Thought (CoT) of multi-step benefits from the logical structure of
the reasoning steps and task-specific actions, significantly enhancing the
mathematical reasoning capabilities of large language models. As the prevalence
of long CoT, the number of reasoning steps exceeds manageable token limits and
leads to higher computational demands. Inspired by the fundamental logic of
human cognition, "derive, then reduce", we conceptualize the standard
multi-step CoT as a novel Markov Chain of Thought (MCoT). In this study, we
consider the mathematical reasoning task, defining each reasoning step as text
accompanied by a Python code snippet. To facilitate a longer reasoning path,
self-correction is enabled through interactions with the code interpreter. Our
MCoT aims to compress previous reasoning steps into a simplified question,
enabling efficient next-step inference without relying on a lengthy KV cache.
In our experiments, we curate the \\(\texttt\{MCoTInstruct\}\\) dataset, and the
empirical results indicate that MCoT not only significantly enhances efficiency
but also maintains comparable accuracy. While much remains to be explored, this
work paves the way for exploring the long CoT reasoning abilities of LLMs. The
code is available at https://github.com/james-yw/Markov-Chain-of-Thought
