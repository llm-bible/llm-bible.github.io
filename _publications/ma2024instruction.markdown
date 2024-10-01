---
layout: publication
title: 'Llamoco: Instruction Tuning Of Large Language Models For Optimization Code Generation'
authors: Ma Zeyuan, Guo Hongshu, Chen Jiacheng, Peng Guojun, Cao Zhiguang, Ma Yining, Gong Yue-jiao
conference: "Arxiv"
year: 2024
bibkey: ma2024instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.01131"}
  - {name: "Code", url: "https://anonymous.4open.science/r/LLaMoCo-722A"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
'Recent research explores optimization using large language models (LLMs) by either iteratively seeking next-step solutions from LLMs or directly prompting LLMs for an optimizer. However, these approaches exhibit inherent limitations, including low operational efficiency, high sensitivity to prompt design, and a lack of domain-specific knowledge. We introduce LLaMoCo, the first instruction-tuning framework designed to adapt LLMs for solving optimization problems in a code-to-code manner. Specifically, we establish a comprehensive instruction set containing well-described problem prompts and effective optimization codes. We then develop a novel two-phase learning strategy that incorporates a contrastive learning-based warm-up procedure before the instruction-tuning phase to enhance the convergence behavior during model fine-tuning. The experiment results demonstrate that a CodeGen (350M) model fine-tuned by our LLaMoCo achieves superior optimization performance compared to GPT-4 Turbo and the other competitors across both synthetic and realistic problem sets. The fine-tuned model and the usage instructions are available at https://anonymous.4open.science/r/LLaMoCo-722A.'
