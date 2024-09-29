---
layout: publication
title: MANGO A Benchmark For Evaluating Mapping And Navigation Abilities Of Large Language Models
authors: Ding Peng, Fang Jiading, Li Peng, Wang Kangrui, Zhou Xiaochen, Yu Mo, Li Jing, Walter Matthew R., Mei Hongyuan
conference: "Arxiv"
year: 2024
bibkey: ding2024benchmark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.19913"}
  - {name: "Code", url: "https://mango.ttic.edu"}
  - {name: "Code", url: "https://github.com/oaklight/mango/"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning']
---
Large language models such as ChatGPT and GPT45;4 have recently achieved astonishing performance on a variety of natural language processing tasks. In this paper we propose MANGO a benchmark to evaluate their capabilities to perform text45;based mapping and navigation. Our benchmark includes 53 mazes taken from a suite of textgames each maze is paired with a walkthrough that visits every location but does not cover all possible paths. The task is question45;answering for each maze a large language model reads the walkthrough and answers hundreds of mapping and navigation questions such as How should you go to Attic from West of House and Where are we if we go north and east from Cellar. Although these questions are easy to humans it turns out that even GPT45;4 the best45;to45;date language model performs poorly at answering them. Further our experiments suggest that a strong mapping and navigation ability would benefit large language models in performing relevant downstream tasks such as playing textgames. Our MANGO benchmark will facilitate future research on methods that improve the mapping and navigation capabilities of language models. We host our leaderboard data code and evaluation program at https://mango.ttic.edu and https://github.com/oaklight/mango/.
