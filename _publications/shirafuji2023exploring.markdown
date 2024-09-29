---
layout: publication
title: "Exploring The Robustness Of Large Language Models For Solving Programming Problems"
authors: Shirafuji Atsushi, Watanobe Yutaka, Ito Takumi, Morishita Makoto, Nakamura Yuki, Oda Yusuke, Suzuki Jun
conference: "Arxiv"
year: 2023
bibkey: shirafuji2023exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.14583"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Security', 'Training Techniques', 'Transformer']
---
Using large language models (LLMs) for source code has recently gained attention. LLMs such as Transformer-based models like Codex and ChatGPT have been shown to be highly capable of solving a wide range of programming problems. However the extent to which LLMs understand problem descriptions and generate programs accordingly or just retrieve source code from the most relevant problem in training data based on superficial cues has not been discovered yet. To explore this research question we conduct experiments to understand the robustness of several popular LLMs CodeGen and GPT-3.5 series models capable of tackling code generation tasks in introductory programming problems. Our experimental results show that CodeGen and Codex are sensitive to the superficial modifications of problem descriptions and significantly impact code generation performance. Furthermore we observe that Codex relies on variable names as randomized variables decrease the solved rate significantly. However the state-of-the-art (SOTA) models such as InstructGPT and ChatGPT show higher robustness to superficial modifications and have an outstanding capability for solving programming problems. This highlights the fact that slight modifications to the prompts given to the LLMs can greatly affect code generation performance and careful formatting of prompts is essential for high-quality code generation while the SOTA models are becoming more robust to perturbations.
