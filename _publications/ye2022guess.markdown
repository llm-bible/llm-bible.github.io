---
layout: publication
title: Guess The Instruction! Flipped Learning Makes Language Models Stronger Zero45;shot Learners
authors: Ye Seonghyeon, Kim Doyoung, Jang Joel, Shin Joongbo, Seo Minjoon
conference: "Arxiv"
year: 2022
bibkey: ye2022guess
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.02969"}
  - {name: "Code", url: "https://github.com/seonghyeonye/Flipped&#45;Learning"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Meta45;training which fine45;tunes the language model (LM) on various downstream tasks by maximizing the likelihood of the target label given the task instruction and input instance has improved the zero45;shot task generalization performance. However meta45;trained LMs still struggle to generalize to challenging tasks containing novel labels unseen during meta45;training. In this paper we propose Flipped Learning an alternative method of meta45;training which trains the LM to generate the task instruction given the input instance and label. During inference the LM trained with Flipped Learning referred to as Flipped selects the label option that is most likely to generate the task instruction. On 14 tasks of the BIG45;bench benchmark the 11B45;sized Flipped outperforms zero45;shot T045;11B and even a 16 times larger 345;shot GPT45;3 (175B) on average by 8.437; and 9.737; points respectively. Flipped gives particularly large improvements on tasks with unseen labels outperforming T045;11B by up to +2037; average F1 score. This indicates that the strong task generalization of Flipped comes from improved generalization to novel labels. We release our code at https://github.com/seonghyeonye/Flipped&#45;Learning.
