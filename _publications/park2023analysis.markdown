---
layout: publication
title: 'On The Analysis Of Cross-lingual Prompt Tuning For Decoder-based Multilingual Model'
authors: Nohil Park, Joonsuk Park, Kang Min Yoo, Sungroh Yoon
conference: "Arxiv"
year: 2023
bibkey: park2023analysis
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07820"}
tags: ['Fine-Tuning', 'GPT', 'Language Modeling', 'Training Techniques', 'Tokenization', 'Pretraining Methods', 'Few-Shot', 'Prompting']
---
An exciting advancement in the field of multilingual models is the emergence
of autoregressive models with zero- and few-shot capabilities, a phenomenon
widely reported in large-scale language models. To further improve model
adaptation to cross-lingual tasks, another trend is to further fine-tune the
language models with either full fine-tuning or parameter-efficient tuning.
However, the interaction between parameter-efficient fine-tuning (PEFT) and
cross-lingual tasks in multilingual autoregressive models has yet to be
studied. Specifically, we lack an understanding of the role of linguistic
distributions in multilingual models in the effectiveness of token-based prompt
tuning. To address this question, we conduct experiments comparing prompt
tuning and fine-tuning on the decoder-based multilingual model, XGLM, with four
cross-lingual tasks (XNLI, PAWS-X, POS, NER). According to our study, prompt
tuning achieves on par or better performance over fine-tuning across all
languages while updating at most 0.13% of the model parameters. Moreover, we
empirically show that prompt tuning is more effective in enhancing the
performance of low-resource languages than fine-tuning. Our further analysis
shows that the phenomenon is related to the tokenization scheme of the
multilingual model.
