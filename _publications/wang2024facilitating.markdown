---
layout: publication
title: 'Metatool: Facilitating Large Language Models To Master Tools With Meta-task Augmentation'
authors: Xiaohan Wang, Dian Li, Yilin Zhao, Sinbadliu, Hui Wang
conference: "Arxiv"
year: 2024
bibkey: wang2024facilitating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12871"}
tags: ['Agentic', 'Model Architecture', 'Training Techniques', 'Few-Shot', 'Tools', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
Utilizing tools with Large Language Models (LLMs) is essential for grounding
AI agents in real-world applications. The prevailing approach involves few-shot
prompting with demonstrations or fine-tuning with expert annotations. However,
mere in-context demonstrations may fail to cover sufficient knowledge for
complex tools and tasks. Training on solution paths is also hindered by the
high cost of expert annotations and generalizing to new tools. A core challenge
of generalizable tool use lies in understanding the "meta", or fundamental
natures of tools that are transferable across tasks, such as causality and
constraints. In this paper, we present MetaTool, a novel tool learning
methodology designed to generalize across any reusable toolset. Our approach
incorporates a self-supervised augmentation technique derived from a series of
meta-tasks. This involves predicting masked elements in the tool execution
process. The self-supervised procedure enables scalable generation of
high-quality QA data, which is handy for supervising tool understanding. By
incorporating meta-task data into task-oriented training, our method
significantly enhances the performance of open-source LLMs, achieving results
comparable to ChatGPT in both tool-based planning and chatting scenarios.
Through large-scale instruction tuning, the MetaTool model demonstrates
impressive zero-shot generalizability on new tasks.
