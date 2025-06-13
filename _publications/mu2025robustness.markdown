---
layout: publication
title: 'Robustness Of Prompting: Enhancing Robustness Of Large Language Models Against Prompting Attacks'
authors: Lin Mu, Guowei Chu, Li Ni, Lei Sang, Zhize Wu, Peiquan Jin, Yiwen Zhang
conference: "Arxiv"
year: 2025
bibkey: mu2025robustness
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.03627'}
tags: ['Reinforcement Learning', 'Prompting', 'Security', 'Applications']
---
Large Language Models (LLMs) have demonstrated remarkable performance across various tasks by effectively utilizing a prompting strategy. However, they are highly sensitive to input perturbations, such as typographical errors or slight character order errors, which can substantially degrade their performance. Despite advances in prompting techniques, developing a prompting strategy that explicitly mitigates the negative impact of such perturbations remains an open challenge. To bridge this gap, we propose Robustness of Prompting (RoP), a novel prompting strategy specifically designed to enhance the robustness of LLMs. RoP consists of two stages: Error Correction and Guidance. In the Error Correction stage, RoP applies diverse perturbation methods to generate adversarial examples, which are then used to construct prompts that automatically correct input errors. In the Guidance stage, RoP generates an optimal guidance prompting based on the corrected input, steering the model toward more robust and accurate inferences. Through comprehensive experiments spanning arithmetic, commonsense, and logical reasoning tasks, we demonstrate that RoP significantly improves LLMs' robustness against adversarial perturbations. Notably, it maintains model accuracy with only minimal degradation compared to clean input scenarios, thereby establishing RoP as a practical and effective approach for enhancing LLM robustness in real-world applications.
