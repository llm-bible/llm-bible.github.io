---
layout: publication
title: 'Biomistral-nlu: Towards More Generalizable Medical Language Understanding Through Instruction Tuning'
authors: Yujuan Velvin Fu, Giridhar Kaushik Ramachandran, Namu Park, Kevin Lybarger, Fei Xia, Ozlem Uzuner, Meliha Yetisgen
conference: "Arxiv"
year: 2024
bibkey: fu2024biomistral
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.18955"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
Large language models (LLMs) such as ChatGPT are fine-tuned on large and
diverse instruction-following corpora, and can generalize to new tasks.
However, those instruction-tuned LLMs often perform poorly in specialized
medical natural language understanding (NLU) tasks that require domain
knowledge, granular text comprehension, and structured data extraction. To
bridge the gap, we: (1) propose a unified prompting format for 7 important NLU
tasks, (2) curate an instruction-tuning dataset, MNLU-Instruct, utilizing
diverse existing open-source medical NLU corpora, and (3) develop
BioMistral-NLU, a generalizable medical NLU model, through fine-tuning
BioMistral on MNLU-Instruct. We evaluate BioMistral-NLU in a zero-shot setting,
across 6 important NLU tasks, from two widely adopted medical NLU benchmarks:
BLUE and BLURB. Our experiments show that our BioMistral-NLU outperforms the
original BioMistral, as well as the proprietary LLMs - ChatGPT and GPT-4. Our
dataset-agnostic prompting strategy and instruction tuning step over diverse
NLU tasks enhance LLMs' generalizability across diverse medical NLU tasks. Our
ablation experiments show that instruction-tuning on a wider variety of tasks,
even when the total number of training instances remains constant, enhances
downstream zero-shot generalization.
