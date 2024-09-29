---
layout: publication
title: Benchmarking And Improving Generator45;validator Consistency Of Language Models
authors: Li Xiang Lisa, Shrivastava Vaishnavi, Li Siyan, Hashimoto Tatsunori, Liang Percy
conference: "Arxiv"
year: 2023
bibkey: li2023benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.01846"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Tools']
---
As of September 2023 ChatGPT correctly answers what is 7+8 with 15 but when asked 7+8=15 True or False it responds with False. This inconsistency between generating and validating an answer is prevalent in language models (LMs) and erodes trust. In this paper we propose a framework for measuring the consistency between generation and validation (which we call generator45;validator consistency or GV45;consistency) finding that even GPT45;4 a state45;of45;the45;art LM is GV45;consistent only 7637; of the time. To improve the consistency of LMs we propose to finetune on the filtered generator and validator responses that are GV45;consistent and call this approach consistency fine45;tuning. We find that this approach improves GV45;consistency of Alpaca45;30B from 6037; to 9337; and the improvement extrapolates to unseen tasks and domains (e.g. GV45;consistency for positive style transfers extrapolates to unseen styles like humor). In addition to improving consistency consistency fine45;tuning improves both generator quality and validator accuracy without using any labeled data. Evaluated across 6 tasks including math questions knowledge45;intensive QA and instruction following our method improves the generator quality by 1637; and the validator accuracy by 6.337; across all tasks.
