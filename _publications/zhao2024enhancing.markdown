---
layout: publication
title: Enhancing Cross45;domain Pre45;trained Decision Transformers With Adaptive Attention
authors: Zhao Wenhao, Xu Qiushui, Xu Linjie, Song Lei, Wang Jinyu, Zhou Chunlai, Bian Jiang
conference: "Arxiv"
year: 2024
bibkey: zhao2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.06985"}
tags: ['Agentic', 'Attention Mechanism', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Recently the pre45;training of decision transformers (DT) using a different domain such as natural language text has generated significant attention in offline reinforcement learning (Offline RL). Although this cross45;domain pre45;training approach achieves superior performance compared to training from scratch in environments required short45;term planning ability the mechanisms by which pre45;training benefits the fine45;tuning phase remain unclear. Furthermore we point out that the cross45;domain pre45;training approach hinders the extraction of distant information in environments like PointMaze that require long45;term planning ability leading to performance that is much worse than training DT from scratch. This work first analyzes these issues and found that Markov Matrix a component that exists in pre45;trained attention heads is the key to explain the significant performance disparity of pre45;trained models in different planning abilities. Inspired by our analysis we propose a general method GPT45;DTMA which equips a pre45;trained DT with Mixture of Attention (MoA) to enable adaptive learning and accommodating diverse attention requirements during fine45;tuning. Extensive experiments demonstrate that the effectiveness of GPT45;DTMA it achieves superior performance in short45;term environments compared to baselines and in long45;term environments it mitigates the negative impact caused by Markov Matrix achieving results comparable to those of DT trained from scratch.
