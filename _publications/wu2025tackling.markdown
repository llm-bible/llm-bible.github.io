---
layout: publication
title: 'Livelongbench: Tackling Long-context Understanding For Spoken Texts From Live Streams'
authors: Yongxuan Wu, Runyu Chen, Peiyu Liu, Hongjin Qian
conference: "Arxiv"
year: 2025
bibkey: wu2025tackling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.17366"}
  - {name: "Code", url: "https://github.com/Yarayx/livelongbench"}
tags: ['Has Code', 'Reinforcement Learning']
---
Long-context understanding poses significant challenges in natural language
processing, particularly for real-world dialogues characterized by speech-based
elements, high redundancy, and uneven information density. Although large
language models (LLMs) achieve impressive results on existing benchmarks, these
datasets fail to reflect the complexities of such texts, limiting their
applicability to practical scenarios. To bridge this gap, we construct the
first spoken long-text dataset, derived from live streams, designed to reflect
the redundancy-rich and conversational nature of real-world scenarios. We
construct tasks in three categories: retrieval-dependent, reasoning-dependent,
and hybrid. We then evaluate both popular LLMs and specialized methods to
assess their ability to understand long-contexts in these tasks. Our results
show that current methods exhibit strong task-specific preferences and perform
poorly on highly redundant inputs, with no single method consistently
outperforming others. We propose a new baseline that better handles redundancy
in spoken text and achieves strong performance across tasks. Our findings
highlight key limitations of current methods and suggest future directions for
improving long-context understanding. Finally, our benchmark fills a gap in
evaluating long-context spoken language understanding and provides a practical
foundation for developing real-world e-commerce systems. The code and benchmark
are available at https://github.com/Yarayx/livelongbench.
