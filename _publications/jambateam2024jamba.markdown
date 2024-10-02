---
layout: publication
title: 'Jamba-1.5: Hybrid Transformer-mamba Models At Scale'
authors: Jamba Team, Lenz Barak, Arazi Alan, Bergman Amir, Manevich Avshalom, Peleg Barak, Aviram Ben, Almagor Chen, Fridman Clara, Padnos Dan, Gissin Daniel, Jannai Daniel, Muhlgay Dor, Zimberg Dor, Gerber Edden M, Dolev Elad, Krakovsky Eran, Safahi Erez, Schwartz Erez, Cohen Gal, Shachaf Gal, Rozenblum Haim, Bata Hofit, Blass Ido, Magar Inbal, Dalmedigos Itay, Osin Jhonathan, Fadlon Julie, Rozman Maria, Danos Matan, Gokhman Michael, Zusman Mor, Gidron Naama, Ratner Nir, Gat Noam, Rozen Noam, Fried Oded, Leshno Ohad, Antverg Omer, Abend Omri, Lieber Opher, Dagan Or, Cohavi Orit, Alon Raz, Belson Ro'i, Cohen Roi, Gilad Rom, Glozman Roman, Lev Shahar, Meirom Shaked, Delbari Tal, Ness Tal, Asida Tomer, Gal Tom Ben, Braude Tom, Pumerantz Uriya, Cohen Yehoshua, Belinkov Yonatan, Globerson Yuval, Levy Yuval Peleg, Shoham Yoav
conference: "Arxiv"
year: 2024
bibkey: jambateam2024jamba
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.12570"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Reinforcement Learning', 'Transformer']
---
'We present Jamba-1.5, new instruction-tuned large language models based on our Jamba architecture. Jamba is a hybrid Transformer-Mamba mixture of experts architecture, providing high throughput and low memory usage across context lengths, while retaining the same or better quality as Transformer models. We release two model sizes: Jamba-1.5-Large, with 94B active parameters, and Jamba-1.5-Mini, with 12B active parameters. Both models are fine-tuned for a variety of conversational and instruction-following capabilties, and have an effective context length of 256K tokens, the largest amongst open-weight models. To support cost-effective inference, we introduce ExpertsInt8, a novel quantization technique that allows fitting Jamba-1.5-Large on a machine with 8 80GB GPUs when processing 256K-token contexts without loss of quality. When evaluated on a battery of academic and chatbot benchmarks, Jamba-1.5 models achieve excellent results while providing high throughput and outperforming other open-weight models on long-context benchmarks. The model weights for both sizes are publicly available under the Jamba Open Model License and we release ExpertsInt8 as open source.'
