---
layout: publication
title: Self45;taught Evaluators
authors: Wang Tianlu, Kulikov Ilia, Golovneva Olga, Yu Ping, Yuan Weizhe, Dwivedi-yu Jane, Pang Richard Yuanzhe, Fazel-zarandi Maryam, Weston Jason, Li Xian
conference: "Arxiv"
year: 2024
bibkey: wang2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.02666"}
tags: ['GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Model45;based evaluation is at the heart of successful model development 45;45; as a reward model for training and as a replacement for human evaluation. To train such evaluators the standard approach is to collect a large amount of human preference judgments over model responses which is costly and the data becomes stale as models improve. In this work we present an approach that aims to im45;prove evaluators without human annotations using synthetic training data only. Starting from unlabeled instructions our iterative self45;improvement scheme generates contrasting model outputs and trains an LLM45;as45;a45;Judge to produce reasoning traces and final judgments repeating this training at each new iteration using the improved predictions. Without any labeled preference data our Self45;Taught Evaluator can improve a strong LLM (Llama345;70B45;Instruct) from 75.4 to 88.3 (88.7 with majority vote) on RewardBench. This outperforms commonly used LLM judges such as GPT45;4 and matches the performance of the top45;performing reward models trained with labeled examples.
