---
layout: publication
title: APT-Pipe A Prompt-Tuning Tool for Social Data Annotation using ChatGPT
authors: Zhu Yiming, Yin Zhizhuo, Tyson Gareth, Haq Ehsan-ul, Lee Lik-hang, Hui Pan
conference: "Arxiv"
year: 2024
bibkey: zhu2024apt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01697"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Recent research has highlighted the potential of LLM applications like ChatGPT for performing label annotation on social computing text. However it is already well known that performance hinges on the quality of the input prompts. To address this there has been a flurry of research into prompt tuning -- techniques and guidelines that attempt to improve the quality of prompts. Yet these largely rely on manual effort and prior knowledge of the dataset being annotated. To address this limitation we propose APT-Pipe an automated prompt-tuning pipeline. APT-Pipe aims to automatically tune prompts to enhance ChatGPTs text classification performance on any given dataset. We implement APT-Pipe and test it across twelve distinct text classification datasets. We find that prompts tuned by APT-Pipe help ChatGPT achieve higher weighted F1-score on nine out of twelve experimented datasets with an improvement of 7.01 on average. We further highlight APT-Pipes flexibility as a framework by showing how it can be extended to support additional tuning mechanisms.
