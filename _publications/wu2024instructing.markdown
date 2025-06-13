---
layout: publication
title: 'Instructing Large Language Models To Identify And Ignore Irrelevant Conditions'
authors: Zhenyu Wu, Chao Shen, Meng Jiang
conference: "Arxiv"
year: 2024
bibkey: wu2024instructing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.12744'}
tags: ['Few-Shot', 'GPT', 'Model Architecture', 'Merging', 'Prompting', 'In-Context Learning']
---
Math word problem (MWP) solving requires generating a reasoning path based on
a given problem description that often contains irrelevant conditions. Existing
chain-of-thought (CoT) prompting methods elicited multi-step reasoning
abilities of large language models (LLMs) to solve MWPs. However, they were
seriously confused by the irrelevant conditions, resulting in low accuracy. In
this paper, we propose a novel approach named I\\(^3\\)C that instructs LLMs to
identify and ignore irrelevant conditions. It identifies a set of irrelevant
condition candidates that have a weak semantic relevance with the question.
Then it prompts LLMs to verify the irrelevant conditions. Lastly it instructs
the LLMs with the verification on relevant and irrelevant conditions to avoid
confusion and improve reasoning paths. Moreover, we propose to select (problem,
reasoning paths) pairs as demonstrations to enhance I\\(^3\\)C with few-shot
reasoning. We develop I\\(^3\\)C-Select that selects the most confusing problems
based on the semantic relevance measurement. We conduct extensive experiments
on eight MWP datasets. I\\(^3\\)C can be combined with any CoT prompting methods to
improve the performance of solving MWPs. Notably, with GPT-3.5-Turbo and
I\\(^3\\)C-Select, we achieve an accuracy of 96.0 and 94.1 on GSM-IC2-1K and
GSM-ICM-1K, respectively, significantly outperforming the state-of-the-art
few-shot prompting method Complex-CoT by +11.7 and +11.1. Our implementation is
made publicly available at https://wzy6642.github.io/I3C.github.io/.
