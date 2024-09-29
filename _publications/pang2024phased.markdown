---
layout: publication
title: Phased Instruction Fine45;tuning For Large Language Models
authors: Pang Wei, Zhou Chuan, Zhou Xiao-hua, Wang Xiaojie
conference: "Arxiv"
year: 2024
bibkey: pang2024phased
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04371"}
  - {name: "Code", url: "https://github.com/xubuvd/PhasedSFT"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning']
---
Instruction Fine45;Tuning enhances pre45;trained language models from basic next45;word prediction to complex instruction45;following. However existing One45;off Instruction Fine45;Tuning (One45;off IFT) method applied on a diverse instruction may not effectively boost models adherence to instructions due to the simultaneous handling of varying instruction complexities. To improve this Phased Instruction Fine45;Tuning (Phased IFT) is proposed based on the idea that learning to follow instructions is a gradual process. It assesses instruction difficulty using GPT45;4 divides the instruction data into subsets of increasing difficulty and uptrains the model sequentially on these subsets. Experiments with Llama45;2 7B/13B/70B Llama3 8/70B and Mistral45;7B models using Alpaca data show that Phased IFT significantly outperforms One45;off IFT supporting the progressive alignment hypothesis and providing a simple and efficient way to enhance large language models. Codes and datasets from our experiments are freely available at https://github.com/xubuvd/PhasedSFT.
