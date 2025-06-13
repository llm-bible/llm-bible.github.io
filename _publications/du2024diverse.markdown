---
layout: publication
title: 'Dflow: Diverse Dialogue Flow Simulation With Large Language Models'
authors: Wanyu Du, Song Feng, James Gung, Lijia Sun, Yi Zhang, Saab Mansour, Yanjun Qi
conference: "Arxiv"
year: 2024
bibkey: du2024diverse
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.14853'}
tags: ['Agentic', 'GPT', 'Model Architecture']
---
Developing language model-based dialogue agents requires effective data to
train models that can follow specific task logic. However, most existing data
simulation methods focus on increasing diversity in language, topics, or
dialogue acts at the utterance level, largely neglecting a critical aspect of
task logic diversity at the dialogue level. This paper proposes a novel data
simulation method designed to enhance the diversity of synthetic dialogues by
focusing on task execution logic. Our method uses LLMs to generate decision
tree-structured task plans, which enables the derivation of diverse dialogue
trajectories for a given task. Each trajectory, referred to as a "dialog flow",
guides the generation of a multi-turn dialogue that follows a unique
trajectory. We apply this method to generate a task-oriented dialogue dataset
comprising 3,886 dialogue flows across 15 different domains. We validate the
effectiveness of this dataset using the next action prediction task, where
models fine-tuned on our dataset outperform strong baselines, including GPT-4.
Upon acceptance of this paper, we plan to release the code and data publicly.
