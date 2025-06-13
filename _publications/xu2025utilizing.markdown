---
layout: publication
title: 'Utilizing Jailbreak Probability To Attack And Safeguard Multimodal Llms'
authors: Wenzhuo Xu, Zhipeng Wei, Xiongtao Sun, Deyue Zhang, Dongdong Yang, Quanchen Zou, Xiangzheng Zhang
conference: "Arxiv"
year: 2025
bibkey: xu2025utilizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.06989"}
tags: ['Responsible AI', 'Efficiency and Optimization', 'Security', 'Multimodal Models', 'Prompting']
---
Recently, Multimodal Large Language Models (MLLMs) have demonstrated their
superior ability in understanding multimodal contents. However, they remain
vulnerable to jailbreak attacks, which exploit weaknesses in their safety
alignment to generate harmful responses. Previous studies categorize jailbreaks
as successful or failed based on whether responses contain malicious content.
However, given the stochastic nature of MLLM responses, this binary
classification of an input's ability to jailbreak MLLMs is inappropriate.
Derived from this viewpoint, we introduce jailbreak probability to quantify the
jailbreak potential of an input, which represents the likelihood that MLLMs
generated a malicious response when prompted with this input. We approximate
this probability through multiple queries to MLLMs. After modeling the
relationship between input hidden states and their corresponding jailbreak
probability using Jailbreak Probability Prediction Network (JPPN), we use
continuous jailbreak probability for optimization. Specifically, we propose
Jailbreak-Probability-based Attack (JPA) that optimizes adversarial
perturbations on inputs to maximize jailbreak probability. To counteract
attacks, we also propose two defensive methods: Jailbreak-Probability-based
Finetuning (JPF) and Jailbreak-Probability-based Defensive Noise (JPDN), which
minimizes jailbreak probability in the MLLM parameters and input space,
respectively. Extensive experiments show that (1) JPA yields improvements (up
to 28.38%) under both white and black box settings compared to previous
methods with small perturbation bounds and few iterations. (2) JPF and JPDN
significantly reduce jailbreaks by at most over 60%. Both of the above results
demonstrate the significance of introducing jailbreak probability to make
nuanced distinctions among input jailbreak abilities.
