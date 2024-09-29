---
layout: publication
title: SGP45;TOD Building Task Bots Effortlessly Via Schema45;guided LLM Prompting
authors: Zhang Xiaoying, Peng Baolin, Li Kun, Zhou Jingyan, Meng Helen
conference: "Arxiv"
year: 2023
bibkey: zhang2023sgp
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.09067"}
tags: ['Applications', 'Prompting', 'Training Techniques']
---
Building end45;to45;end task bots and maintaining their integration with new functionalities using minimal human efforts is a long45;standing challenge in dialog research. Recently large language models (LLMs) have demonstrated exceptional proficiency in conversational engagement and adherence to instructions across various downstream tasks. In this work we introduce SGP45;TOD Schema45;Guided Prompting for building Task45;Oriented Dialog systems effortlessly based on LLMs. Utilizing the symbolic knowledge 45;45; task schema we instruct fixed LLMs to generate appropriate responses on novel tasks circumventing the need for training data. Specifically SGP45;TOD comprises three components a LLM for engaging with users a DST Prompter to aid the LLM with dialog state tracking which is then used to retrieve database items and a Policy Prompter to elicit proper responses adhering to the provided dialog policy. Experimental results on Multiwoz RADDLE and STAR datasets show that our training45;free strategy SGP45;TOD without any task45;specific data yields state45;of45;the45;art (SOTA) zero45;shot performance greatly surpasses the few45;shot approaches. In a domain45;extension setting SGP45;TOD aptly adapts to new functionalities by merely adding supplementary schema rules. We make our code and data publicly available.
