---
layout: publication
title: Prompt Tuning For Discriminative Pre45;trained Language Models
authors: Yao Yuan, Dong Bowen, Zhang Ao, Zhang Zhengyan, Xie Ruobing, Liu Zhiyuan, Lin Leyu, Sun Maosong, Wang Jianyong
conference: "Arxiv"
year: 2022
bibkey: yao2022prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.11166"}
  - {name: "Code", url: "https://github.com/thunlp/DPT"}
tags: ['Applications', 'BERT', 'Has Code', 'Language Modeling', 'Model Architecture', 'Prompting', 'Tools']
---
Recent works have shown promising results of prompt tuning in stimulating pre45;trained language models (PLMs) for natural language processing (NLP) tasks. However to the best of our knowledge existing works focus on prompt45;tuning generative PLMs that are pre45;trained to generate target tokens such as BERT. It is still unknown whether and how discriminative PLMs e.g. ELECTRA can be effectively prompt45;tuned. In this work we present DPT the first prompt tuning framework for discriminative PLMs which reformulates NLP tasks into a discriminative language modeling problem. Comprehensive experiments on text classification and question answering show that compared with vanilla fine45;tuning DPT achieves significantly higher performance and also prevents the unstable problem in tuning large PLMs in both full45;set and low45;resource settings. The source code and experiment details of this paper can be obtained from https://github.com/thunlp/DPT.
