---
layout: publication
title: 'Labeling Supervised Fine-tuning Data With The Scaling Law'
authors: Huanjun Kong
conference: "Arxiv"
year: 2024
bibkey: kong2024labeling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.02817"}
  - {name: "Code", url: "https://github.com/InternLM/HuixiangDou/tree/main/web/tools),"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'RAG', 'Model Architecture', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
This paper introduces a multi-stage manual annotation calibrated by the
scaling law, offering a high-quality Supervised Fine-Tuning data acquisition
method for environments with constrained resources like GPU poor, limited GPT
access, and funding restrictions. We have preprocessed 58k authentic chat data
and manually annotated 2.3k questions. After this, we conducted fine-tuning on
Qwen models, ranging from 0.5B to 32B parameters. The optimal version improved
29.07 in F1 score. This confirms the viability of fine-tuning Large Language
Model (LLM) for downstream Natural Language Processing (NLP) tasks. Our
contributions are: 1) Created Supervised Fine-Tuning (SFT) training data in
alpaca format, along with a set of Low-Rank Adaptation (LoRA) weights, and 2)
Developed a method for acquiring high-quality data leveraging scaling law
principle. The script, raw data with alpaca format and experiments track are
open-sourced on Github
(https://github.com/InternLM/HuixiangDou/tree/main/web/tools), HuggingFace
(https://huggingface.co/tpoisonooo) and WandB
(https://wandb.ai/tpoisonooo/huixiangdou-cr/table?nw=nwusertpoisonooo). The
privacy of the data involved has been authorized by users. SFT data and license
comes from ncnn contributors group.
