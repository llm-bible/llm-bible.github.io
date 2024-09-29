---
layout: publication
title: Towards Making The Most Of Multilingual Pretraining For Zero45;shot Neural Machine Translation
authors: Chen Guanhua, Ma Shuming, Chen Yun, Zhang Dongdong, Pan Jia, Wang Wenping, Wei Furu
conference: "Arxiv"
year: 2021
bibkey: chen2021towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.08547"}
tags: ['Applications', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
This paper demonstrates that multilingual pretraining and multilingual fine45;tuning are both critical for facilitating cross45;lingual transfer in zero45;shot translation where the neural machine translation (NMT) model is tested on source languages unseen during supervised training. Following this idea we present SixT+ a strong many45;to45;English NMT model that supports 100 source languages but is trained with a parallel dataset in only six source languages. SixT+ initializes the decoder embedding and the full encoder with XLM45;R large and then trains the encoder and decoder layers with a simple two45;stage training strategy. SixT+ achieves impressive performance on many45;to45;English translation. It significantly outperforms CRISS and m2m45;100 two strong multilingual NMT systems with an average gain of 7.2 and 5.0 BLEU respectively. Additionally SixT+ offers a set of model parameters that can be further fine45;tuned to other unsupervised tasks. We demonstrate that adding SixT+ initialization outperforms state45;of45;the45;art explicitly designed unsupervised NMT models on Si<45;En and Ne<45;En by over 1.2 average BLEU. When applied to zero45;shot cross45;lingual abstractive summarization it produces an average performance gain of 12.3 ROUGE45;L over mBART45;ft. We conduct detailed analyses to understand the key ingredients of SixT+ including multilinguality of the auxiliary parallel data positional disentangled encoder and the cross45;lingual transferability of its encoder.
