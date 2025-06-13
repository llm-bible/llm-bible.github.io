---
layout: publication
title: 'Large Language Models Can Be Guided To Evade Ai-generated Text Detection'
authors: Ning Lu, Shengcai Liu, Rui He, Qi Wang, Yew-soon Ong, Ke Tang
conference: "Arxiv"
year: 2023
bibkey: lu2023large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.10847'}
  - {name: "Code", url: 'https://github.com/ColinLu50/Evade-GPT-Detector'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Security', 'Model Architecture', 'GPT', 'Prompting', 'Reinforcement Learning']
---
Large language models (LLMs) have shown remarkable performance in various
tasks and have been extensively utilized by the public. However, the increasing
concerns regarding the misuse of LLMs, such as plagiarism and spamming, have
led to the development of multiple detectors, including fine-tuned classifiers
and statistical methods. In this study, we equip LLMs with prompts, rather than
relying on an external paraphraser, to evaluate the vulnerability of these
detectors. We propose a novel Substitution-based In-Context example
Optimization method (SICO) to automatically construct prompts for evading the
detectors. SICO is cost-efficient as it requires only 40 human-written examples
and a limited number of LLM inferences to generate a prompt. Moreover, once a
task-specific prompt has been constructed, it can be universally used against a
wide range of detectors. Extensive experiments across three real-world tasks
demonstrate that SICO significantly outperforms the paraphraser baselines and
enables GPT-3.5 to successfully evade six detectors, decreasing their AUC by
0.5 on average. Furthermore, a comprehensive human evaluation show that the
SICO-generated text achieves human-level readability and task completion rates,
while preserving high imperceptibility. Finally, we propose an ensemble
approach to enhance the robustness of detectors against SICO attack. The code
is publicly available at https://github.com/ColinLu50/Evade-GPT-Detector.
