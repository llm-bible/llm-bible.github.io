---
layout: publication
title: 'Bigcodebench: Benchmarking Code Generation With Diverse Function Calls And Complex Instructions'
authors: Zhuo Terry Yue, Vu Minh Chien, Chim Jenny, Hu Han, Yu Wenhao, Widyasari Ratnadira, Yusuf Imam Nur Bani, Zhan Haolan, He Junda, Paul Indraneil, Brunner Simon, Gong Chen, Hoang Thong, Zebaze Armel Randy, Hong Xiaoheng, Li Wen-ding, Kaddour Jean, Xu Ming, Zhang Zhihan, Yadav Prateek, Jain Naman, Gu Alex, Cheng Zhoujun, Liu Jiawei, Liu Qian, Wang Zijian, Lo David, Hui Binyuan, Muennighoff Niklas, Fried Daniel, Du Xiaoning, De Vries Harm, Von Werra Leandro
conference: "Arxiv"
year: 2024
bibkey: zhuo2024benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.15877"}
tags: ['Applications', 'RAG', 'Tools']
---
Automated software engineering has been greatly empowered by the recent
advances in Large Language Models (LLMs) for programming. While current
benchmarks have shown that LLMs can perform various software engineering tasks
like human developers, the majority of their evaluations are limited to short
and self-contained algorithmic tasks. Solving challenging and practical
programming tasks requires the capability of utilizing diverse function calls
as tools to efficiently implement functionalities like data analysis and web
development. In addition, using multiple tools to solve a task needs
compositional reasoning by accurately understanding complex instructions.
Fulfilling both of these characteristics can pose a great challenge for LLMs.
To assess how well LLMs can solve challenging and practical programming tasks,
we introduce Bench, a benchmark that challenges LLMs to invoke multiple
function calls as tools from 139 libraries and 7 domains for 1,140 fine-grained
programming tasks. To evaluate LLMs rigorously, each programming task
encompasses 5.6 test cases with an average branch coverage of 99%. In addition,
we propose a natural-language-oriented variant of Bench, Benchi, that
automatically transforms the original docstrings into short instructions only
with essential information. Our extensive evaluation of 60 LLMs shows that LLMs
are not yet capable of following complex instructions to use function calls
precisely, with scores up to 60%, significantly lower than the human
performance of 97%. The results underscore the need for further advancements in
this area.
