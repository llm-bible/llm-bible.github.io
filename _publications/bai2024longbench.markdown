---
layout: publication
title: 'Longbench V2: Towards Deeper Understanding And Reasoning On Realistic Long-context Multitasks'
authors: Yushi Bai, Shangqing Tu, Jiajie Zhang, Hao Peng, Xiaozhi Wang, Xin Lv, Shulin Cao, Jiazheng Xu, Lei Hou, Yuxiao Dong, Jie Tang, Juanzi Li
conference: "Arxiv"
year: 2024
bibkey: bai2024longbench
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15204"}
  - {name: "Code", url: "https://longbench2.github.io"}
tags: ['Survey Paper', 'Reinforcement Learning', 'Has Code', 'Prompting', 'In-Context Learning']
---
This paper introduces LongBench v2, a benchmark designed to assess the
ability of LLMs to handle long-context problems requiring deep understanding
and reasoning across real-world multitasks. LongBench v2 consists of 503
challenging multiple-choice questions, with contexts ranging from 8k to 2M
words, across six major task categories: single-document QA, multi-document QA,
long in-context learning, long-dialogue history understanding, code repository
understanding, and long structured data understanding. To ensure the breadth
and the practicality, we collect data from nearly 100 highly educated
individuals with diverse professional backgrounds. We employ both automated and
manual review processes to maintain high quality and difficulty, resulting in
human experts achieving only 53.7% accuracy under a 15-minute time constraint.
Our evaluation reveals that the best-performing model, when directly answers
the questions, achieves only 50.1% accuracy. In contrast, the o1-preview model,
which includes longer reasoning, achieves 57.7%, surpassing the human baseline
by 4%. These results highlight the importance of enhanced reasoning ability and
scaling inference-time compute to tackle the long-context challenges in
LongBench v2. The project is available at https://longbench2.github.io.
