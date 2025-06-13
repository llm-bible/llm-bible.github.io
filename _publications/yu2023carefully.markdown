---
layout: publication
title: 'Kola: Carefully Benchmarking World Knowledge Of Large Language Models'
authors: Jifan Yu, Xiaozhi Wang, Shangqing Tu, Shulin Cao, Daniel Zhang-li, Xin Lv, Hao Peng, Zijun Yao, Xiaohan Zhang, Hanming Li, Chunyang Li, Zheyuan Zhang, Yushi Bai, Yantao Liu, Amy Xin, Nianyi Lin, Kaifeng Yun, Linlu Gong, Jianhui Chen, Zhili Wu, Yunjia Qi, Weikai Li, Yong Guan, Kaisheng Zeng, Ji Qi, Hailong Jin, Jinxin Liu, Yu Gu, Yuan Yao, Ning Ding, Lei Hou, Zhiyuan Liu, Bin Xu, Jie Tang, Juanzi Li
conference: "Arxiv"
year: 2023
bibkey: yu2023carefully
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2306.09296'}
tags: ['Reinforcement Learning', 'Ethics and Bias', 'Merging']
---
The unprecedented performance of large language models (LLMs) necessitates
improvements in evaluations. Rather than merely exploring the breadth of LLM
abilities, we believe meticulous and thoughtful designs are essential to
thorough, unbiased, and applicable evaluations. Given the importance of world
knowledge to LLMs, we construct a Knowledge-oriented LLM Assessment benchmark
(KoLA), in which we carefully design three crucial factors: (1) For
\textbf\{ability modeling\}, we mimic human cognition to form a four-level
taxonomy of knowledge-related abilities, covering \\(19\\) tasks. (2) For
\textbf\{data\}, to ensure fair comparisons, we use both Wikipedia, a corpus
prevalently pre-trained by LLMs, along with continuously collected emerging
corpora, aiming to evaluate the capacity to handle unseen data and evolving
knowledge. (3) For \textbf\{evaluation criteria\}, we adopt a contrastive system,
including overall standard scores for better numerical comparability across
tasks and models and a unique self-contrast metric for automatically evaluating
knowledge-creating ability. We evaluate \\(28\\) open-source and commercial LLMs
and obtain some intriguing findings. The KoLA dataset and open-participation
leaderboard are publicly released at https://kola.xlore.cn and will be
continuously updated to provide references for developing LLMs and
knowledge-related systems.
