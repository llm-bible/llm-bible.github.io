---
layout: publication
title: On The Analysis Of Cross45;lingual Prompt Tuning For Decoder45;based Multilingual Model
authors: Park Nohil, Park Joonsuk, Yoo Kang Min, Yoon Sungroh
conference: "Arxiv"
year: 2023
bibkey: park2023analysis
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07820"}
tags: ['Fine Tuning', 'GPT', 'Language Modeling', 'Pretraining Methods', 'Prompting', 'Tokenization']
---
An exciting advancement in the field of multilingual models is the emergence of autoregressive models with zero45; and few45;shot capabilities a phenomenon widely reported in large45;scale language models. To further improve model adaptation to cross45;lingual tasks another trend is to further fine45;tune the language models with either full fine45;tuning or parameter45;efficient tuning. However the interaction between parameter45;efficient fine45;tuning (PEFT) and cross45;lingual tasks in multilingual autoregressive models has yet to be studied. Specifically we lack an understanding of the role of linguistic distributions in multilingual models in the effectiveness of token45;based prompt tuning. To address this question we conduct experiments comparing prompt tuning and fine45;tuning on the decoder45;based multilingual model XGLM with four cross45;lingual tasks (XNLI PAWS45;X POS NER). According to our study prompt tuning achieves on par or better performance over fine45;tuning across all languages while updating at most 0.1337; of the model parameters. Moreover we empirically show that prompt tuning is more effective in enhancing the performance of low45;resource languages than fine45;tuning. Our further analysis shows that the phenomenon is related to the tokenization scheme of the multilingual model.
