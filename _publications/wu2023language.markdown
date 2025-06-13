---
layout: publication
title: 'Language Prompt For Autonomous Driving'
authors: Dongming Wu, Wencheng Han, Yingfei Liu, Tiancai Wang, Cheng-zhong Xu, Xiangyu Zhang, Jianbing Shen
conference: "Arxiv"
year: 2023
bibkey: wu2023language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.04379"}
  - {name: "Code", url: "https://github.com/wudongming97/Prompt4Driving"}
tags: ['Model Architecture', 'RAG', 'Pretraining Methods', 'Transformer', 'Has Code', 'Prompting']
---
A new trend in the computer vision community is to capture objects of
interest following flexible human command represented by a natural language
prompt. However, the progress of using language prompts in driving scenarios is
stuck in a bottleneck due to the scarcity of paired prompt-instance data. To
address this challenge, we propose the first object-centric language prompt set
for driving scenes within 3D, multi-view, and multi-frame space, named
NuPrompt. It expands nuScenes dataset by constructing a total of 40,147
language descriptions, each referring to an average of 7.4 object tracklets.
Based on the object-text pairs from the new benchmark, we formulate a novel
prompt-based driving task, \ie, employing a language prompt to predict the
described object trajectory across views and frames. Furthermore, we provide a
simple end-to-end baseline model based on Transformer, named PromptTrack.
Experiments show that our PromptTrack achieves impressive performance on
NuPrompt. We hope this work can provide some new insights for the self-driving
community. The data and code have been released at
https://github.com/wudongming97/Prompt4Driving.
