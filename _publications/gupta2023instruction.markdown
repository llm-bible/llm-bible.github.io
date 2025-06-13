---
layout: publication
title: 'Instruction Tuned Models Are Quick Learners'
authors: Himanshu Gupta, Saurabh Arjun Sawant, Swaroop Mishra, Mutsumi Nakamura, Arindam Mitra, Santosh Mashetty, Chitta Baral
conference: "Arxiv"
year: 2023
bibkey: gupta2023instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.05539"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
Instruction tuning of language models has demonstrated the ability to enhance
model generalization to unseen tasks via in-context learning using a few
examples. However, typical supervised learning still requires a plethora of
downstream training data for finetuning. Often in real-world situations, there
is a scarcity of data available for finetuning, falling somewhere between few
shot inference and fully supervised finetuning. In this work, we demonstrate
the sample efficiency of instruction tuned models over various tasks by
estimating the minimal downstream training data required by them to perform
transfer learning and match the performance of state-of-the-art (SOTA)
supervised models. We conduct experiments on 119 tasks from Super Natural
Instructions (SuperNI) in both the single task learning (STL) and multi task
learning (MTL) settings. Our findings reveal that, in the STL setting,
instruction tuned models equipped with 25% of the downstream train data surpass
the SOTA performance on the downstream tasks. In the MTL setting, an
instruction tuned model trained on only 6% of downstream training data achieve
SOTA, while using 100% of the training data results in a 3.69% points
improvement (ROUGE-L 74.68) over the previous SOTA. We conduct an analysis on
T5 vs Tk-Instruct by developing several baselines to demonstrate that
instruction tuning aids in increasing both sample efficiency and transfer
learning. Additionally, we observe a consistent ~4% performance increase in
both settings when pre-finetuning is performed with instructions. Finally, we
conduct a categorical study and find that contrary to previous results, tasks
in the question rewriting and title generation categories suffer from
instruction tuning.
