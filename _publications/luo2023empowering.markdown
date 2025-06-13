---
layout: publication
title: 'Wizardmath: Empowering Mathematical Reasoning For Large Language Models Via Reinforced Evol-instruct'
authors: Haipeng Luo, Qingfeng Sun, Can Xu, Pu Zhao, Jianguang Lou, Chongyang Tao, Xiubo Geng, Qingwei Lin, Shifeng Chen, Yansong Tang, Dongmei Zhang
conference: "Arxiv"
year: 2023
bibkey: luo2023empowering
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2308.09583'}
  - {name: "Code", url: 'https://github.com/nlpxucan/WizardLM'}
tags: ['Agentic', 'Has Code', 'Efficiency and Optimization', 'Model Architecture', 'GPT', 'Tools', 'Fine-Tuning', 'Reinforcement Learning']
---
Large language models (LLMs), such as GPT-4, have shown remarkable performance in natural language processing (NLP) tasks, including challenging mathematical reasoning. However, most existing open-source models are only pre-trained on large-scale internet data and without math-related optimization. In this paper, we present WizardMath, which enhances the mathematical CoT reasoning abilities of LLMs without using external python tools, by applying our proposed Reinforcement Learning from Evol-Instruct Feedback (RLEIF) method to the domain of math. Through extensive experiments on two mathematical reasoning benchmarks, namely GSM8k and MATH, we reveal the extraordinary capabilities of our model. Remarkably, WizardMath-Mistral 7B surpasses top-tier open-source LLMs by a substantial margin with higher data efficiency. Furthermore, WizardMath 70B even outperforms GPT-3.5-Turbo, Claude 2, Gemini Pro and GPT-4-early-version. Additionally, our preliminary exploration highlights the pivotal role of instruction evolution and process supervision in achieving exceptional math performance. For more details refer to https://github.com/nlpxucan/WizardLM
