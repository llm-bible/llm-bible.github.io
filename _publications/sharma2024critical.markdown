---
layout: publication
title: A Critical Evaluation Of AI Feedback For Aligning Large Language Models
authors: Sharma Archit, Keh Sedrick, Mitchell Eric, Finn Chelsea, Arora Kushal, Kollar Thomas
conference: "Arxiv"
year: 2024
bibkey: sharma2024critical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.12366"}
tags: ['Agentic', 'Fine Tuning', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Reinforcement Learning']
---
Reinforcement learning with AI feedback (RLAIF) is a popular paradigm for improving the instruction45;following abilities of powerful pre45;trained language models. RLAIF first performs supervised fine45;tuning (SFT) using demonstrations from a teacher model and then further fine45;tunes the model with reinforcement learning (RL) using feedback from a critic model. While recent popular open45;source models have demonstrated substantial improvements in performance from the RL step in this paper we question whether the complexity of this RL step is truly warranted for AI feedback. We show that the improvements of the RL step are virtually entirely due to the widespread practice of using a weaker teacher model (e.g. GPT45;3.5) for SFT data collection than the critic (e.g. GPT45;4) used for AI feedback generation. Specifically we show that simple supervised fine45;tuning with GPT45;4 as the teacher outperforms existing RLAIF pipelines. More generally we find that the gains from RLAIF vary substantially across base model families test45;time evaluation protocols and critic models. Finally we provide a mechanistic explanation for when SFT may outperform the full two45;step RLAIF pipeline as well as suggestions for making RLAIF maximally useful in practice.
