---
layout: publication
title: 'Unveiling The Pitfalls Of Knowledge Editing For Large Language Models'
authors: Zhoubo Li, Ningyu Zhang, Yunzhi Yao, Mengru Wang, Xi Chen, Huajun Chen
conference: "Arxiv"
year: 2023
bibkey: li2023unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.02129"}
  - {name: "Code", url: "https://github.com/zjunlp/PitfallsKnowledgeEditing"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Attention Mechanism']
---
As the cost associated with fine-tuning Large Language Models (LLMs)
continues to rise, recent research efforts have pivoted towards developing
methodologies to edit implicit knowledge embedded within LLMs. Yet, there's
still a dark cloud lingering overhead -- will knowledge editing trigger
butterfly effect? since it is still unclear whether knowledge editing might
introduce side effects that pose potential risks or not. This paper pioneers
the investigation into the potential pitfalls associated with knowledge editing
for LLMs. To achieve this, we introduce new benchmark datasets and propose
innovative evaluation metrics. Our results underline two pivotal concerns: (1)
Knowledge Conflict: Editing groups of facts that logically clash can magnify
the inherent inconsistencies in LLMs-a facet neglected by previous methods. (2)
Knowledge Distortion: Altering parameters with the aim of editing factual
knowledge can irrevocably warp the innate knowledge structure of LLMs.
Experimental results vividly demonstrate that knowledge editing might
inadvertently cast a shadow of unintended consequences on LLMs, which warrant
attention and efforts for future works. Code and data are available at
https://github.com/zjunlp/PitfallsKnowledgeEditing.
