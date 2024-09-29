---
layout: publication
title: Multilingual Speech Translation With Efficient Finetuning Of Pretrained Models
authors: Li Xian, Wang Changhan, Tang Yun, Tran Chau, Tang Yuqing, Pino Juan, Baevski Alexei, Conneau Alexis, Auli Michael
conference: "Arxiv"
year: 2020
bibkey: li2020multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.12829"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'Language Modeling', 'Model Architecture', 'RAG', 'Training Techniques']
---
We present a simple yet effective approach to build multilingual speech45;to45;text (ST) translation by efficient transfer learning from pretrained speech encoder and text decoder. Our key finding is that a minimalistic LNA (LayerNorm and Attention) finetuning can achieve zero45;shot crosslingual and cross45;modality transfer ability by only finetuning less than 1037; of the pretrained parameters. This enables effectively leveraging large pretrained models with low training cost. Using wav2vec 2.0 for acoustic modeling and mBART for multilingual text generation our approach advanced the new state45;of45;the45;art for 34 translation directions (and surpassing cascaded ST for 23 of them) on large45;scale multilingual ST benchmark CoVoST 2 (+6.4 BLEU on average across 15 En45;X directions and +5.1 BLEU on average across 19 X45;En directions). Our approach demonstrates strong zero45;shot performance in a many45;to45;many multilingual model (+5.7 BLEU on average across 18 non45;English directions) making it an appealing approach for attaining high45;quality speech translation with improved parameter and data efficiency.
