---
layout: publication
title: "An LLM Can Fool Itself: A Prompt-based Adversarial Attack"
authors: Xu Xilie, Kong Keyi, Liu Ning, Cui Lizhen, Wang Di, Zhang Jingfeng, Kankanhalli Mohan
conference: "Arxiv"
year: 2023
bibkey: xu2023llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.13345"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Responsible AI', 'Security']
---
The wide-ranging applications of large language models (LLMs) especially in safety-critical domains necessitate the proper evaluation of the LLMs adversarial robustness. This paper proposes an efficient tool to audit the LLMs adversarial robustness via a prompt-based adversarial attack (PromptAttack). PromptAttack converts adversarial textual attacks into an attack prompt that can cause the victim LLM to output the adversarial sample to fool itself. The attack prompt is composed of three important components (1) original input (OI) including the original sample and its ground-truth label (2) attack objective (AO) illustrating a task description of generating a new sample that can fool itself without changing the semantic meaning and (3) attack guidance (AG) containing the perturbation instructions to guide the LLM on how to complete the task by perturbing the original sample at character word and sentence levels respectively. Besides we use a fidelity filter to ensure that PromptAttack maintains the original semantic meanings of the adversarial examples. Further we enhance the attack power of PromptAttack by ensembling adversarial examples at different perturbation levels. Comprehensive empirical results using Llama2 and GPT-3.5 validate that PromptAttack consistently yields a much higher attack success rate compared to AdvGLUE and AdvGLUE++. Interesting findings include that a simple emoji can easily mislead GPT-3.5 to make wrong predictions.
