---
layout: publication
title: Cross45;lingual Knowledge Editing In Large Language Models
authors: Wang Jiaan, Liang Yunlong, Sun Zengkui, Cao Yuxuan, Xu Jiarong, Meng Fandong
conference: "Arxiv"
year: 2023
bibkey: wang2023cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.08952"}
  - {name: "Code", url: "https://github.com/krystalan/Bi&#95;ZsRE"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Knowledge editing aims to change language models performance on several special cases (i.e. editing scope) by infusing the corresponding expected knowledge into them. With the recent advancements in large language models (LLMs) knowledge editing has been shown as a promising technique to adapt LLMs to new knowledge without retraining from scratch. However most of the previous studies neglect the multi45;lingual nature of some main45;stream LLMs (e.g. LLaMA ChatGPT and GPT45;4) and typically focus on monolingual scenarios where LLMs are edited and evaluated in the same language. As a result it is still unknown the effect of source language editing on a different target language. In this paper we aim to figure out this cross45;lingual effect in knowledge editing. Specifically we first collect a large45;scale cross45;lingual synthetic dataset by translating ZsRE from English to Chinese. Then we conduct English editing on various knowledge editing methods covering different paradigms and evaluate their performance in Chinese and vice versa. To give deeper analyses of the cross45;lingual effect the evaluation includes four aspects i.e. reliability generality locality and portability. Furthermore we analyze the inconsistent behaviors of the edited models and discuss their specific challenges. Data and codes are available at https://github.com/krystalan/Bi&#95;ZsRE
