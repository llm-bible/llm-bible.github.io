---
layout: publication
title: Self45;rewarding Language Models
authors: Yuan Weizhe, Pang Richard Yuanzhe, Cho Kyunghyun, Li Xian, Sukhbaatar Sainbayar, Xu Jing, Weston Jason
conference: "Arxiv"
year: 2024
bibkey: yuan2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.10020"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
We posit that to achieve superhuman agents future models require superhuman feedback in order to provide an adequate training signal. Current approaches commonly train reward models from human preferences which may then be bottlenecked by human performance level and secondly these separate frozen reward models cannot then learn to improve during LLM training. In this work we study Self45;Rewarding Language Models where the language model itself is used via LLM45;as45;a45;Judge prompting to provide its own rewards during training. We show that during Iterative DPO training that not only does instruction following ability improve but also the ability to provide high45;quality rewards to itself. Fine45;tuning Llama 2 70B on three iterations of our approach yields a model that outperforms many existing systems on the AlpacaEval 2.0 leaderboard including Claude 2 Gemini Pro and GPT45;4 0613. While there is much left still to explore this work opens the door to the possibility of models that can continually improve in both axes.
