---
layout: publication
title: 'Human-instruction-free LLM Self-alignment With Limited Samples'
authors: Hongyi Guo, Yuanshun Yao, Wei Shen, Jiaheng Wei, Xiaoying Zhang, Zhaoran Wang, Yang Liu
conference: "Arxiv"
year: 2024
bibkey: guo2024human
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.06785"}
tags: ['Responsible AI', 'Prompting', 'In-Context Learning', 'Reinforcement Learning']
---
Aligning large language models (LLMs) with human values is a vital task for
LLM practitioners. Current alignment techniques have several limitations: (1)
requiring a large amount of annotated data; (2) demanding heavy human
involvement; (3) lacking a systematic mechanism to continuously improve. In
this work, we study aligning LLMs to a new domain with limited samples (e.g. <
100). We propose an algorithm that can self-align LLMs iteratively without
active human involvement. Unlike existing works, our algorithm relies on
neither human-crafted instructions nor labeled rewards, significantly reducing
human involvement. In addition, our algorithm can self-improve the alignment
continuously. The key idea is to first retrieve high-quality samples related to
the target domain and use them as In-context Learning examples to generate more
samples. Then we use the self-generated samples to finetune the LLM
iteratively. We show that our method can unlock the LLMs' self-generalization
ability to perform alignment with near-zero human supervision. We test our
algorithm on three benchmarks in safety, truthfulness, and
instruction-following, and show good performance in alignment, domain
adaptability, and scalability.
