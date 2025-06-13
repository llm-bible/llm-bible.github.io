---
layout: publication
title: 'Prompting And Fine-tuning Large Language Models For Automated Code Review Comment Generation'
authors: Md. Asif Haider, Ayesha Binte Mostofa, Sk. Sabit Bin Mosaddek, Anindya Iqbal, Toufique Ahmed
conference: "Arxiv"
year: 2024
bibkey: haider2024prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.10129"}
tags: ['Training Techniques', 'Model Architecture', 'Few-Shot', 'Survey Paper', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
Generating accurate code review comments remains a significant challenge due
to the inherently diverse and non-unique nature of the task output. Large
language models pretrained on both programming and natural language data tend
to perform well in code-oriented tasks. However, large-scale pretraining is not
always feasible due to its environmental impact and project-specific
generalizability issues. In this work, first we fine-tune open-source Large
language models (LLM) in parameter-efficient, quantized low-rank (QLoRA)
fashion on consumer-grade hardware to improve review comment generation. Recent
studies demonstrate the efficacy of augmenting semantic metadata information
into prompts to boost performance in other code-related tasks. To explore this
in code review activities, we also prompt proprietary, closed-source LLMs
augmenting the input code patch with function call graphs and code summaries.
Both of our strategies improve the review comment generation performance, with
function call graph augmented few-shot prompting on the GPT-3.5 model
surpassing the pretrained baseline by around 90% BLEU-4 score on the
CodeReviewer dataset. Moreover, few-shot prompted Gemini-1.0 Pro, QLoRA
fine-tuned Code Llama and Llama 3.1 models achieve competitive results (ranging
from 25% to 83% performance improvement) on this task. An additional human
evaluation study further validates our experimental findings, reflecting
real-world developers' perceptions of LLM-generated code review comments based
on relevant qualitative metrics.
