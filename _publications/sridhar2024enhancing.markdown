---
layout: publication
title: "Enhancing Temporal Understanding In Audio Question Answering For Large Audio Language Models"
authors: Sridhar Arvind Krishna, Guo Yinyi, Visser Erik
conference: "Arxiv"
year: 2024
bibkey: sridhar2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.06223"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture']
---
The Audio Question Answering task includes audio event classification audio captioning and open ended reasoning. Recently Audio Question Answering has garnered attention due to the advent of Large Audio Language Models. Current literature focuses on constructing LALMs by integrating audio encoders with text only Large Language Models through a projection module. While Large Audio Language Models excel in general audio understanding they are limited in temporal reasoning which may hinder their commercial applications and on device deployment. This paper addresses these challenges and limitations in audio temporal reasoning. First we introduce a data augmentation technique for generating reliable audio temporal questions and answers using an LLM. Second we propose a continued finetuning curriculum learning strategy to specialize in temporal reasoning without compromising performance on finetuned tasks. Finally we develop a reliable and transparent automated metric assisted by an LLM to measure the correlation between Large Audio Language Model responses and ground truth data intelligently. We demonstrate the effectiveness of our proposed techniques using SOTA LALMs on public audio benchmark datasets.
