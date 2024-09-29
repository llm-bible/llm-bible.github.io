---
layout: publication
title: Aligner Efficient Alignment By Learning To Correct
authors: Ji Jiaming, Chen Boyuan, Lou Hantao, Hong Donghai, Zhang Borong, Pan Xuehai, Dai Juntao, Qiu Tianyi, Yang Yaodong
conference: "Arxiv"
year: 2024
bibkey: ji2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.02416"}
tags: ['GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
With the rapid development of large language models (LLMs) and ever45;evolving practical requirements finding an efficient and effective alignment method has never been more critical. However the tension between the complexity of current alignment methods and the need for rapid iteration in deployment scenarios necessitates the development of a model45;agnostic alignment approach that can operate under these constraints. In this paper we introduce Aligner a novel and simple alignment paradigm that learns the correctional residuals between preferred and dispreferred answers using a small model. Designed as a model45;agnostic plug45;and45;play module Aligner can be directly applied to various open45;source and API45;based models with only one45;off training making it suitable for rapid iteration. Notably Aligner can be applied to any powerful large45;scale upstream models. Moreover it can even iteratively bootstrap the upstream models using corrected responses as synthetic human preference data breaking through the models performance ceiling. Our experiments demonstrate performance improvements by deploying the same Aligner model across 11 different LLMs evaluated on the 3H dimensions (helpfulness harmlessness and honesty). Specifically Aligner45;7B has achieved an average improvement of 68.937; in helpfulness and 23.837; in harmlessness across the tested LLMs while also effectively reducing hallucination. In the Alpaca45;Eval leaderboard stacking Aligner45;2B on GPT45;4 Turbo improved its LC Win Rate from 55.037; to 58.337; surpassing GPT45;4 Omnis 57.537; Win Rate (community report).
