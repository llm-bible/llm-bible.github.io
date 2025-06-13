---
layout: publication
title: 'Multi-agent Collaboration For Multilingual Code Instruction Tuning'
authors: Jian Yang, Wei Zhang, Jiaxi Yang, Yibo Miao, Shanghaoran Quan, Zhenhe Wu, Qiyao Peng, Liqun Yang, Tianyu Liu, Zeyu Cui, Binyuan Hui, Junyang Lin
conference: "Arxiv"
year: 2025
bibkey: yang2025multi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.07487'}
tags: ['RAG', 'Agentic', 'Tools']
---
Recent advancement in code understanding and generation demonstrates that
code LLMs fine-tuned on a high-quality instruction dataset can gain powerful
capabilities to address wide-ranging code-related tasks. However, most previous
existing methods mainly view each programming language in isolation and ignore
the knowledge transfer among different programming languages. To bridge the gap
among different programming languages, we introduce a novel multi-agent
collaboration framework to enhance multilingual instruction tuning for code
LLMs, where multiple language-specific intelligent agent components with
generation memory work together to transfer knowledge from one language to
another efficiently and effectively. Specifically, we first generate the
language-specific instruction data from the code snippets and then provide the
generated data as the seed data for language-specific agents. Multiple
language-specific agents discuss and collaborate to formulate a new instruction
and its corresponding solution (A new programming language or existing
programming language), To further encourage the cross-lingual transfer, each
agent stores its generation history as memory and then summarizes its merits
and faults. Finally, the high-quality multilingual instruction data is used to
encourage knowledge transfer among different programming languages to train
Qwen2.5-xCoder. Experimental results on multilingual programming benchmarks
demonstrate the superior performance of Qwen2.5-xCoder in sharing common
knowledge, highlighting its potential to reduce the cross-lingual gap.
