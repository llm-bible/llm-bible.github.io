---
layout: publication
title: 'Lawgpt: Knowledge-guided Data Generation And Its Application To Legal LLM'
authors: Zhi Zhou, Kun-yang Yu, Shi-yu Tian, Xiao-wen Yang, Jiang-xin Shi, Pengxiao Song, Yi-xuan Jin, Lan-zhe Guo, Yu-feng Li
conference: "Arxiv"
year: 2025
bibkey: zhou2025knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.06572"}
  - {name: "Code", url: "https://github.com/LAMDASZ-ML/Knowledge-Guide-Data-Generation"}
tags: ['Tools', 'GPT', 'RAG', 'Model Architecture', 'Training Techniques', 'Has Code']
---
Large language models (LLMs), both proprietary and open-source, have
demonstrated remarkable capabilities across various natural language processing
tasks. However, they face significant limitations in legal reasoning tasks.
Proprietary models introduce data privacy risks and high inference costs, while
open-source models underperform due to insufficient legal domain training data.
To address these limitations, we study data generation for legal reasoning to
improve the legal reasoning performance of open-source LLMs with the help of
proprietary LLMs. This is challenging due to the lack of legal knowledge in
proprietary LLMs and the difficulty in verifying the generated data. We propose
KgDG, a knowledge-guided data generation framework for legal reasoning. Our
framework enables leveraging legal knowledge to enhance generation diversity
and introduces a refinement and verification process to ensure the quality of
generated data. Moreover, we expand the generated dataset to further enhance
the LLM reasoning capabilities. Using KgDG, we create a synthetic legal
reasoning dataset containing 50K high-quality examples. Our trained model
LawGPT outperforms existing legal-specific LLMs and achieves performance
comparable to proprietary LLMs, demonstrating the effectiveness of KgDG and
LawGPT. Our code and resources is publicly available at
https://github.com/LAMDASZ-ML/Knowledge-Guide-Data-Generation .
