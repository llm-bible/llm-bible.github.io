---
layout: publication
title: 'Instructalign: High-and-low Resource Language Alignment Via Continual Crosslingual Instruction Tuning'
authors: Cahyawijaya Samuel, Lovenia Holy, Yu Tiezheng, Chung Willy, Fung Pascale
conference: "Arxiv"
year: 2023
bibkey: cahyawijaya2023high
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13627"}
  - {name: "Code", url: "https://github.com/HLTCHKUST/InstructAlign"}
tags: ['Has Code', 'Pretraining Methods', 'Reinforcement Learning']
---
Large language models (LLMs) that are tuned with instructions have demonstrated remarkable capabilities in various tasks and languages. However, their ability to generalize to underrepresented languages is limited due to the scarcity of available data. Additionally, directly adapting new languages to instruction-tuned LLMs can result in catastrophic forgetting, which leads to the loss of multitasking ability. To address this issue, we propose InstructAlign which uses continual crosslingual instruction tuning to enable LLMs to align new unseen languages with previously learned high-resource languages. Our results demonstrate the effectiveness of InstructAlign in enabling the model to understand low-resource languages with limited parallel data while preventing catastrophic forgetting. Our work contributes to the advancement of language adaptation methods, particularly for adapting instruction-tuned LLMs to underrepresented languages. Our code is released on https://github.com/HLTCHKUST/InstructAlign
