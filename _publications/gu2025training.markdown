---
layout: publication
title: 'Ultraedit: Training-, Subject-, And Memory-free Lifelong Editing In Large Language Models'
authors: Xiaojie Gu, Guangxu Chen, Jungang Li, Jia-chen Gu, Xuming Hu, Kai Zhang
conference: "Arxiv"
year: 2025
bibkey: gu2025training
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.14679'}
  - {name: "Code", url: 'https://github.com/XiaojieGu/UltraEdit'}
tags: ['Reinforcement Learning', 'Has Code', 'Training Techniques']
---
Lifelong learning enables large language models (LLMs) to adapt to evolving information by continually updating their internal knowledge. An ideal system should support efficient, wide-ranging updates while preserving existing capabilities and ensuring reliable deployment. Model editing stands out as a promising solution for this goal, offering a focused and efficient way to revise a model's internal knowledge. Although recent paradigms have made notable progress, they often struggle to meet the demands of practical lifelong adaptation at scale. To bridge this gap, we propose ULTRAEDIT-a fundamentally new editing solution that is training-, subject- and memory-free, making it particularly well-suited for ultra-scalable, real-world lifelong model editing. ULTRAEDIT performs editing through a self-contained process that relies solely on lightweight linear algebra operations to compute parameter shifts, enabling fast and consistent parameter modifications with minimal overhead. To improve scalability in lifelong settings, ULTRAEDIT employs a lifelong normalization strategy that continuously updates feature statistics across turns, allowing it to adapt to distributional shifts and maintain consistency over time. ULTRAEDIT achieves editing speeds over 7x faster than the previous state-of-the-art method-which was also the fastest known approach-while consuming less than 1/3 the VRAM, making it the only method currently capable of editing a 7B LLM on a 24GB consumer-grade GPU. Furthermore, we construct ULTRAEDITBENCH-the largest dataset in the field to date, with over 2M editing pairs-and demonstrate that our method supports up to 1M edits while maintaining high accuracy. Comprehensive experiments on four datasets and six models show that ULTRAEDIT consistently achieves superior performance across diverse model editing scenarios. Our code is available at: https://github.com/XiaojieGu/UltraEdit.
