---
layout: publication
title: 'Metaladder: Ascending Mathematical Solution Quality Via Analogical-problem Reasoning Transfer'
authors: Honglin Lin, Zhuoshi Pan, Yu Li, Qizhi Pei, Xin Gao, Mengzhang Cai, Conghui He, Lijun Wu
conference: "Arxiv"
year: 2025
bibkey: lin2025ascending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.14891"}
  - {name: "Code", url: "https://github.com/LHL3341/MetaLadder"}
tags: ['Prompting', 'RAG', 'Has Code', 'Tools']
---
Large Language Models (LLMs) have demonstrated promising capabilities in
solving mathematical reasoning tasks, leveraging Chain-of-Thought (CoT) data as
a vital component in guiding answer generation. Current paradigms typically
generate CoT and answers directly for a given problem, diverging from human
problem-solving strategies to some extent. Humans often solve problems by
recalling analogous cases and leveraging their solutions to reason about the
current task. Inspired by this cognitive process, we propose
\textbf\{MetaLadder\}, a novel framework that explicitly prompts LLMs to recall
and reflect on meta-problems, those structurally or semantically analogous
problems, alongside their CoT solutions before addressing the target problem.
Additionally, we introduce a problem-restating mechanism to enhance the model's
comprehension of the target problem by regenerating the original question,
which further improves reasoning accuracy. Therefore, the model can achieve
reasoning transfer from analogical problems, mimicking human-like "learning
from examples" and generalization abilities. Extensive experiments on
mathematical benchmarks demonstrate that our MetaLadder significantly boosts
LLMs' problem-solving accuracy, largely outperforming standard CoT-based
methods (\textbf\{10.3%\} accuracy gain) and other methods. Our code and data
has been released at https://github.com/LHL3341/MetaLadder.
