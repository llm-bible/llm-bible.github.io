---
layout: publication
title: 'On The Robustness Of Multimodal Language Model Towards Distractions'
authors: Ming Liu, Hao Chen, Jindong Wang, Wensheng Zhang
conference: "Arxiv"
year: 2025
bibkey: liu2025robustness
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.09818'}
tags: ['Security', 'Model Architecture', 'Applications', 'GPT', 'Prompting', 'Multimodal Models', 'Reinforcement Learning']
---
Although vision-language models (VLMs) have achieved significant success in
various applications such as visual question answering, their resilience to
prompt variations remains an under-explored area. Understanding how
distractions affect VLMs is crucial for improving their real-world
applicability, as inputs could have noisy and irrelevant information in many
practical scenarios. This paper aims to assess the robustness of VLMs against
both visual and textual distractions in the context of science question
answering. Built on the ScienceQA dataset, we developed a new benchmark that
introduces distractions in both the visual and textual contexts to evaluate the
reasoning capacity of VLMs amid these distractions. Our findings reveal that
most-of-the-art VLMs, including GPT-4, are vulnerable to various types of
distractions, experiencing noticeable degradation in reasoning capabilities
when confronted with distractions. Notably, models such as InternVL2
demonstrate a higher degree of robustness to these distractions. We also found
that models exhibit greater sensitivity to textual distractions than visual
ones. Additionally, we explored various mitigation strategies, such as prompt
engineering, to counteract the impact of distractions. While these strategies
improved solution accuracy, our analysis shows that there remain significant
opportunities for improvement.
