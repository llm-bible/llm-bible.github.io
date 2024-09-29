---
layout: publication
title: Autodroid Llm45;powered Task Automation In Android
authors: Wen Hao, Li Yuanchun, Liu Guohong, Zhao Shanhui, Yu Tao, Li Toby Jia-jun, Jiang Shiqi, Liu Yunhao, Zhang Yaqin, Liu Yunxin
conference: "Arxiv"
year: 2023
bibkey: wen2023llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.15272"}
  - {name: "Code", url: "https://autodroid&#45;sys.github.io/&#125;"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Mobile task automation is an attractive technique that aims to enable voice45;based hands45;free user interaction with smartphones. However existing approaches suffer from poor scalability due to the limited language understanding ability and the non45;trivial manual efforts required from developers or end45;users. The recent advance of large language models (LLMs) in language understanding and reasoning inspires us to rethink the problem from a model45;centric perspective where task preparation comprehension and execution are handled by a unified language model. In this work we introduce AutoDroid a mobile task automation system capable of handling arbitrary tasks on any Android application without manual efforts. The key insight is to combine the commonsense knowledge of LLMs and domain45;specific knowledge of apps through automated dynamic analysis. The main components include a functionality45;aware UI representation method that bridges the UI with the LLM exploration45;based memory injection techniques that augment the app45;specific domain knowledge of LLM and a multi45;granularity query optimization module that reduces the cost of model inference. We integrate AutoDroid with off45;the45;shelf LLMs including online GPT45;4/GPT45;3.5 and on45;device Vicuna and evaluate its performance on a new benchmark for memory45;augmented Android task automation with 158 common tasks. The results demonstrated that AutoDroid is able to precisely generate actions with an accuracy of 90.937; and complete tasks with a success rate of 71.337; outperforming the GPT45;445;powered baselines by 36.437; and 39.737;. The demo benchmark suites and source code of AutoDroid will be released at url123;https://autodroid&#45;sys.github.io/&#125;.
