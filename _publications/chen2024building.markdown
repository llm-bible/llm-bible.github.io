---
layout: publication
title: Reinstruct Building Instruction Data From Unlabeled Corpus
authors: Chen Shu, Guan Xinyan, Lu Yaojie, Lin Hongyu, Han Xianpei, Sun Le
conference: "Arxiv"
year: 2024
bibkey: chen2024building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10663"}
  - {name: "Code", url: "https://github.com/cs32963/REInstruct&#125;"}
tags: ['Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Manually annotating instruction data for large language models is difficult costly and hard to scale. Meanwhile current automatic annotation methods typically rely on distilling synthetic data from proprietary LLMs which not only limits the upper bound of the quality of the instruction data but also raises potential copyright issues. In this paper we propose REInstruct a simple and scalable method to automatically build instruction data from an unlabeled corpus without heavy reliance on proprietary LLMs and human annotation. Specifically REInstruct first selects a subset of unlabeled texts that potentially contain well45;structured helpful and insightful content and then generates instructions for these texts. To generate accurate and relevant responses for effective and robust training REInstruct further proposes a rewriting45;based approach to improve the quality of the generated instruction data. By training Llama45;7b on a combination of 3k seed data and 32k synthetic data from REInstruct fine45;tuned model achieves a 65.4137; win rate on AlpacaEval leaderboard against text45;davinci45;003 outperforming other open45;source non45;distilled instruction data construction methods. The code is publicly available at url123;https://github.com/cs32963/REInstruct&#125;.
