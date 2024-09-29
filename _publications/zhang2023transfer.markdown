---
layout: publication
title: Vpgtrans Transfer Visual Prompt Generator Across Llms
authors: Zhang Ao, Fei Hao, Yao Yuan, Ji Wei, Li Li, Liu Zhiyuan, Chua Tat-seng
conference: "Arxiv"
year: 2023
bibkey: zhang2023transfer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.01278"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Multimodal Models', 'Prompting', 'Tools', 'Training Techniques']
---
While developing a new multimodal LLM (MLLM) by pre45;training on tremendous image45;text pairs from scratch can be exceedingly resource45;consuming connecting an existing LLM with a comparatively lightweight visual prompt generator (VPG) becomes a feasible paradigm. However further tuning the VPG part of the MLLM still suffers from indispensable computational costs i.e. requiring thousands of GPU hours and millions of training data. One alternative solution is to transfer an existing VPG from any existing MLLMs for the target MLLM. In this work we for the first time investigate the VPG transferability across LLMs and explore a solution to reduce the cost of VPG transfer. We first study the VPG transfer across different LLM sizes (e.g. small45;to45;large) and across different LLM types through which we diagnose the key factors to maximize the transfer efficiency. Based on our observation we design a two45;stage transfer framework named VPGTrans which is simple yet highly effective. Through extensive experiments we demonstrate that VPGTrans helps significantly speed up the transfer learning process without compromising performance. Remarkably it helps achieve the VPG transfer from BLIP45;2 OPT95;text123;2.7B125; to BLIP45;2 OPT95;text123;6.7B125; with over 10 times speed45;up and 10.737; training data compared with connecting a VPG to OPT95;text123;6.7B125; from scratch. Further a series of intriguing findings and potential rationales behind them are provided and discussed. Finally we showcase the practical value of our VPGTrans approach by customizing two novel MLLMs including VL45;LLaMA and VL45;Vicuna with recently released LLaMA and Vicuna LLMs.
