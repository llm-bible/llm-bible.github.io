---
layout: publication
title: 'Investigating The Influence Of Prompt-specific Shortcuts In AI Generated Text Detection'
authors: Choonghyun Park, Hyuhng Joon Kim, Junyeob Kim, Youna Kim, Taeuk Kim, Hyunsoo Cho, Hwiyeol Jo, Sang-goo Lee, Kang Min Yoo
conference: "Arxiv"
year: 2024
bibkey: park2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16275"}
  - {name: "Code", url: "https://github.com/zxcvvxcz/FAILOpt"}
tags: ['Security', 'Efficiency and Optimization', 'Has Code', 'Prompting']
---
AI Generated Text (AIGT) detectors are developed with texts from humans and
LLMs of common tasks. Despite the diversity of plausible prompt choices, these
datasets are generally constructed with a limited number of prompts. The lack
of prompt variation can introduce prompt-specific shortcut features that exist
in data collected with the chosen prompt, but do not generalize to others. In
this paper, we analyze the impact of such shortcuts in AIGT detection. We
propose Feedback-based Adversarial Instruction List Optimization (FAILOpt), an
attack that searches for instructions deceptive to AIGT detectors exploiting
prompt-specific shortcuts. FAILOpt effectively drops the detection performance
of the target detector, comparable to other attacks based on adversarial
in-context examples. We also utilize our method to enhance the robustness of
the detector by mitigating the shortcuts. Based on the findings, we further
train the classifier with the dataset augmented by FAILOpt prompt. The
augmented classifier exhibits improvements across generation models, tasks, and
attacks. Our code will be available at https://github.com/zxcvvxcz/FAILOpt.
