---
layout: publication
title: 'Showing Llm-generated Code Selectively Based On Confidence Of Llms'
authors: Jia Li, Yuqi Zhu, Yongmin Li, Ge Li, Zhi Jin
conference: "Arxiv"
year: 2024
bibkey: li2024showing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.03234'}
tags: ['Security', 'Applications']
---
Large Language Models (LLMs) have shown impressive abilities in code
generation, but they may generate erroneous programs. Reading a program takes
ten times longer than writing it. Showing these erroneous programs to
developers will waste developers' energies and introduce security risks to
software.
  To address the above limitations, we propose HonestCoder, a novel LLM-based
code generation approach. HonestCoder selectively shows the generated programs
to developers based on LLMs' confidence. The confidence provides valuable
insights into the correctness of generated programs. To achieve this goal, we
propose a novel approach to estimate LLMs' confidence in code generation. It
estimates confidence by measuring the multi-modal similarity between
LLMs-generated programs.
  We collect and release a multilingual benchmark named TruthCodeBench, which
consists of 2,265 samples and covers two popular programming languages (i.e.,
Python and Java). We apply HonestCoder to four popular LLMs (e.g.,
DeepSeek-Coder and Code Llama) and evaluate it on TruthCodeBench. Based on the
experiments, we obtain the following insights. (1) HonestCoder can effectively
estimate LLMs' confidence and accurately determine the correctness of generated
programs. For example, HonestCoder outperforms the state-of-the-art baseline by
27.79% in AUROC and 63.74% in AUCPR. (2) HonestCoder can decrease the number of
erroneous programs shown to developers. Compared to eight baselines, it can
show more correct programs and fewer erroneous programs to developers. (3)
Compared to showing code indiscriminately, HonestCoder only adds slight time
overhead (approximately 0.4 seconds per requirement). (4) We discuss future
directions to facilitate the application of LLMs in software development. We
hope this work can motivate broad discussions about measuring the reliability
of LLMs' outputs in performing code-related tasks.
