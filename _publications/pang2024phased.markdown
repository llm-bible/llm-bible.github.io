---
layout: publication
title: 'Phased Instruction Fine-tuning For Large Language Models'
authors: Pang Wei, Zhou Chuan, Zhou Xiao-hua, Wang Xiaojie
conference: "Arxiv"
year: 2024
bibkey: pang2024phased
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04371"}
  - {name: "Code", url: "https://github.com/xubuvd/PhasedSFT"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Instruction Fine-Tuning enhances pre-trained language models from basic next-word prediction to complex instruction-following. However existing One-off Instruction Fine-Tuning (One-off IFT) method applied on a diverse instruction may not effectively boost models adherence to instructions due to the simultaneous handling of varying instruction complexities. To improve this Phased Instruction Fine-Tuning (Phased IFT) is proposed based on the idea that learning to follow instructions is a gradual process. It assesses instruction difficulty using GPT-4 divides the instruction data into subsets of increasing difficulty and uptrains the model sequentially on these subsets. Experiments with Llama-2 7B/13B/70B Llama3 8/70B and Mistral-7B models using Alpaca data show that Phased IFT significantly outperforms One-off IFT supporting the progressive alignment hypothesis and providing a simple and efficient way to enhance large language models. Codes and datasets from our experiments are freely available at https://github.com/xubuvd/PhasedSFT."
