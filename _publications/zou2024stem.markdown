---
layout: publication
title: 'STEM-POM: Evaluating Language Models Math-symbol Reasoning In Document Parsing'
authors: Jiaru Zou, Qing Wang, Pratyush Thakur, Nickvash Kani
conference: "Arxiv"
year: 2024
bibkey: zou2024stem
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.00387"}
  - {name: "Code", url: "https://github.com/jiaruzouu/STEM-PoM"}
tags: ['Arxiv', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Prompting', 'In-Context Learning']
---
Advances in large language models (LLMs) have spurred research into enhancing their reasoning capabilities, particularly in math-rich STEM (Science, Technology, Engineering, and Mathematics) documents. While LLMs can generate equations or solve math-related queries, their ability to fully understand and interpret abstract mathematical symbols in long, math-rich documents remains limited. In this paper, we introduce STEM-PoM, a comprehensive benchmark dataset designed to evaluate LLMs' reasoning abilities on math symbols within contextual scientific text. The dataset, sourced from real-world ArXiv documents, contains over 2K math symbols classified as main attributes of variables, constants, operators, and unit descriptors, with additional sub-attributes including scalar/vector/matrix for variables and local/global/discipline-specific labels for both constants and operators. Our extensive experiments demonstrate that state-of-the-art LLMs achieve an average accuracy of 20-60% under in-context learning and 50-60% with fine-tuning, highlighting a substantial gap in their ability to classify mathematical symbols. By improving LLMs' mathematical symbol classification, STEM-PoM further enhances models' downstream mathematical reasoning capabilities. The code and data are available at https://github.com/jiaruzouu/STEM-PoM.
