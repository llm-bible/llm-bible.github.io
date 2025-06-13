---
layout: publication
title: 'Can Multimodal Llms Do Visual Temporal Understanding And Reasoning? The Answer Is No!'
authors: Mohamed Fazli Imam, Chenyang Lyu, Alham Fikri Aji
conference: "Arxiv"
year: 2025
bibkey: imam2025can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.10674'}
tags: ['RAG', 'GPT', 'Applications', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
Multimodal Large Language Models (MLLMs) have achieved significant
advancements in tasks like Visual Question Answering (VQA) by leveraging
foundational Large Language Models (LLMs). However, their abilities in specific
areas such as visual temporal understanding, which is crucial for comprehending
real-world dynamics, remain underexplored. To address this, we propose a
challenging evaluation benchmark named TemporalVQA, consisting of two parts: 1)
Temporal Order Understanding and 2) Time-lapse Estimation. The first part
requires MLLMs to determine the sequence of events by analyzing temporally
consecutive video frames. The second part presents image pairs with varying
time differences, framed as multiple-choice questions, asking MLLMs to estimate
the time-lapse between images with options ranging from seconds to years. Our
evaluations of advanced MLLMs, including models like GPT-4o and Gemini-1.5-Pro,
reveal significant challenges: GPT-4o achieved only 49.1% average consistent
accuracy in temporal order task and 70% in time-lapse estimation, with
open-source models performing even poorly. These findings underscore the
limitations of current MLLMs in visual temporal understanding and reasoning,
highlighting the need for further improvements for their temporal capability.
Our dataset can be found at
https://huggingface.co/datasets/fazliimam/temporal-vqa.
