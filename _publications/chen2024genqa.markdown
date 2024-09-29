---
layout: publication
title: Genqa Generating Millions Of Instructions From A Handful Of Prompts
authors: Chen Jiuhai, Qadri Rifaa, Wen Yuxin, Jain Neel, Kirchenbauer John, Zhou Tianyi, Goldstein Tom
conference: "Arxiv"
year: 2024
bibkey: chen2024genqa
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10323"}
tags: ['Pretraining Methods', 'Prompting']
---
Most public instruction finetuning datasets are relatively small compared to the closed source datasets used to train industry models. To study questions about finetuning at scale such as curricula and learning rate cooldown schedules there is a need for industrial-scale datasets. However this scale necessitates a data generation process that is almost entirely automated. In this work we study methods for generating large instruction datasets from a single prompt. With little human oversight we get LLMs to write diverse sets of instruction examples ranging from simple completion tasks to complex multi-turn dialogs across a variety of subject areas. When finetuning a Llama-3 8B base model our dataset meets or exceeds both WizardLM and Ultrachat on both knowledge-intensive leaderboard tasks as well as conversational evaluations. We release our dataset the generator prompts that created it and our finetuned model checkpoints.
