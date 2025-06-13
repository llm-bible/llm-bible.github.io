---
layout: publication
title: 'Nus-emo At Semeval-2024 Task 3: Instruction-tuning LLM For Multimodal Emotion-cause Analysis In Conversations'
authors: Meng Luo, Han Zhang, Shengqiong Wu, Bobo Li, Hong Han, Hao Fei
conference: "Arxiv"
year: 2024
bibkey: luo2024nus
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.17261"}
tags: ['Fine-Tuning', 'Tools', 'RAG', 'Model Architecture', 'Multimodal Models']
---
This paper describes the architecture of our system developed for Task 3 of
SemEval-2024: Multimodal Emotion-Cause Analysis in Conversations. Our project
targets the challenges of subtask 2, dedicated to Multimodal Emotion-Cause Pair
Extraction with Emotion Category (MECPE-Cat), and constructs a dual-component
system tailored to the unique challenges of this task. We divide the task into
two subtasks: emotion recognition in conversation (ERC) and emotion-cause pair
extraction (ECPE). To address these subtasks, we capitalize on the abilities of
Large Language Models (LLMs), which have consistently demonstrated
state-of-the-art performance across various natural language processing tasks
and domains. Most importantly, we design an approach of emotion-cause-aware
instruction-tuning for LLMs, to enhance the perception of the emotions with
their corresponding causal rationales. Our method enables us to adeptly
navigate the complexities of MECPE-Cat, achieving a weighted average 34.71% F1
score of the task, and securing the 2nd rank on the leaderboard. The code and
metadata to reproduce our experiments are all made publicly available.
