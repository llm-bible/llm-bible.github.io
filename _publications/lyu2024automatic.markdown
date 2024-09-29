---
layout: publication
title: 'Automatic Summarization Of Doctor-patient Encounter Dialogues Using Large Language Model Through Prompt Tuning'
authors: Lyu Mengxian, Peng Cheng, Li Xiaohan, Balian Patrick, Bian Jiang, Wu Yonghui
conference: "Arxiv"
year: 2024
bibkey: lyu2024automatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.13089"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Automatic text summarization (ATS) is an emerging technology to assist clinicians in providing continuous and coordinated care. This study presents an approach to summarize doctor-patient dialogues using generative large language models (LLMs). We developed prompt-tuning algorithms to instruct generative LLMs to summarize clinical text. We examined the prompt-tuning strategies the size of soft prompts and the few-short learning ability of GatorTronGPT a generative clinical LLM developed using 277 billion clinical and general English words with up to 20 billion parameters. We compared GatorTronGPT with a previous solution based on fine-tuning of a widely used T5 model using a clinical benchmark dataset MTS-DIALOG. The experimental results show that the GatorTronGPT- 20B model achieved the best performance on all evaluation metrics. The proposed solution has a low computing cost as the LLM parameters are not updated during prompt-tuning. This study demonstrates the efficiency of generative clinical LLMs for clinical ATS through prompt tuning.
