---
layout: publication
title: 'Turbofuzzllm: Turbocharging Mutation-based Fuzzing For Effectively Jailbreaking Large Language Models In Practice'
authors: Aman Goel, Xian Carrie Wu, Zhe Wang, Dmitriy Bespalov, Yanjun Qi
conference: "Arxiv"
year: 2025
bibkey: goel2025turbocharging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.18504'}
  - {name: "Code", url: 'https://github.com/amazon-science/TurboFuzzLLM'}
tags: ['Has Code', 'Efficiency and Optimization', 'Security', 'GPT', 'Model Architecture', 'Prompting']
---
Jailbreaking large-language models (LLMs) involves testing their robustness against adversarial prompts and evaluating their ability to withstand prompt attacks that could elicit unauthorized or malicious responses. In this paper, we present TurboFuzzLLM, a mutation-based fuzzing technique for efficiently finding a collection of effective jailbreaking templates that, when combined with harmful questions, can lead a target LLM to produce harmful responses through black-box access via user prompts. We describe the limitations of directly applying existing template-based attacking techniques in practice, and present functional and efficiency-focused upgrades we added to mutation-based fuzzing to generate effective jailbreaking templates automatically. TurboFuzzLLM achieves \\(\geq\\) 95% attack success rates (ASR) on public datasets for leading LLMs (including GPT-4o \& GPT-4 Turbo), shows impressive generalizability to unseen harmful questions, and helps in improving model defenses to prompt attacks. TurboFuzzLLM is available open source at https://github.com/amazon-science/TurboFuzzLLM.
