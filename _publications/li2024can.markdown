---
layout: publication
title: Can multiple-choice questions really be useful in detecting the abilities of alms
authors: Li Wangyue, Li Liangzhi, Xiang Tong, Liu Xiao, Deng Wei, Garcia Noa
conference: "Arxiv"
year: 2024
bibkey: li2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.17752"}
  - {name: "Code", url: "https://github.com/Meetyou-AI-Lab/Can-MC-Evaluate-LLMs"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Reinforcement Learning']
---
Multiple-choice questions (MCQs) are widely used in the evaluation of large language models (LLMs) due to their simplicity and efficiency. However there are concerns about whether MCQs can truly measure LLMs capabilities particularly in knowledge-intensive scenarios where long-form generation (LFG) answers are required. The misalignment between the task and the evaluation method demands a thoughtful analysis of MCQs efficacy which we undertake in this paper by evaluating nine LLMs on four question-answering (QA) datasets in two languages Chinese and English. We identify a significant issue LLMs exhibit an order sensitivity in bilingual MCQs favoring answers located at specific positions i.e. the first position. We further quantify the gap between MCQs and long-form generation questions (LFGQs) by comparing their direct outputs token logits and embeddings. Our results reveal a relatively low correlation between answers from MCQs and LFGQs for identical questions. Additionally we propose two methods to quantify the consistency and confidence of LLMs output which can be generalized to other QA evaluation benchmarks. Notably our analysis challenges the idea that the higher the consistency the greater the accuracy. We also find MCQs to be less reliable than LFGQs in terms of expected calibration error. Finally the misalignment between MCQs and LFGQs is not only reflected in the evaluation performance but also in the embedding space. Our code and models can be accessed at https://github.com/Meetyou-AI-Lab/Can-MC-Evaluate-LLMs.
