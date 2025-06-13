---
layout: publication
title: 'DCR: Divide-and-conquer Reasoning For Multi-choice Question Answering With Llms'
authors: Zijie Meng, Yan Zhang, Zhaopeng Feng, Zuozhu Liu
conference: "Arxiv"
year: 2024
bibkey: meng2024divide
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.05190"}
  - {name: "Code", url: "https://github.com/AiMijie/Divide-and-Conquer"}
tags: ['Model Architecture', 'Reinforcement Learning', 'RAG', 'Has Code', 'Applications', 'Attention Mechanism']
---
Large language models (LLMs) have shown impressive performance in reasoning
benchmarks with the emergence of Chain-of-Thought (CoT), particularly in
multi-choice question (MCQ). However, current works equally resolve questions
regardless of the problem-solving difficulty, leading to an excessive focus on
simple items while insufficient attention on intricate ones. To address this
challenge, we propose a simple yet effective strategy, Divide and Conquer
Reasoning (DCR), to enhance the reasoning capability of LLMs for MCQs, as
inspired by human beings using heuristics to first categorize tasks and then
handle them separately. In particular, we first categorize questions into two
subsets based on confidence score (\\(\mathcal\{CS\}\\)), which is estimated by
statistical frequency of generated answers. Subsequently, we propose Filter
Choices based Reasoning (FCR) to improve model performance on MCQs with low
(\\(\mathcal\{CS\}\\)). Our experiments demonstrate that the proposed strategy only
costs 85% of SOTA, while still achieves average accuracy improvement of 1.56%
across nine datasets including arithmetic, commonsense, and logic reasoning
tasks. The code is at \url\{https://github.com/AiMijie/Divide-and-Conquer\}
