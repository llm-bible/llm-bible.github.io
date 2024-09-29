---
layout: publication
title: "PARAMANU-GANITA: Language Model With Mathematical Capabilities"
authors: Niyogi Mitodru, Bhattacharya Arnab
conference: "Arxiv"
year: 2024
bibkey: niyogi2024paramanu
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.14395"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
In this paper we present Paramanu-Ganita a 208 million parameter novel Auto Regressive (AR) decoder based language model on mathematics. The model is pretrained from scratch at context size of 4096 on our curated mixed mathematical corpus. We evaluate our model on both perplexity metric and GSM8k mathematical benchmark. Paramanu-Ganita despite being 35 times smaller than 7B LLMs outperformed generalist LLMs such as LLaMa-1 7B by 28.437; points LLaMa-2 7B by 27.637; points Falcon 7B by 32.637; points PaLM 8B by 35.337; points and math specialised LLMs such as Minerva 8B by 23.237; points and LLEMMA-7B by 3.037; points in GSM8k test accuracy metric respectively. Paramanu-Ganita also outperformed giant LLMs like PaLM 62B by 6.437; points Falcon 40B by 19.837; points LLaMa-1 33B by 3.837; points and Vicuna 13B by 11.837; points respectively. The large significant margin improvement in performance of our math model over the existing LLMs signifies that reasoning capabilities of language model are just not restricted to LLMs with humongous number of parameters. Paramanu-Ganita took 146 hours of A100 training whereas math specialised LLM LLEMMA 7B was trained for 23000 A100 hours of training equivalent. Thus our approach of pretraining powerful domain specialised language models from scratch for domain adaptation is much more cost-effective than performing continual training of LLMs for domain adaptation. Hence we conclude that for strong mathematical reasoning abilities of language model we do not need giant LLMs and immense computing power to our end. In the end we want to point out that we have only trained Paramanu-Ganita only on a part of our entire mathematical corpus and yet to explore the full potential of our model.
