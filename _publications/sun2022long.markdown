---
layout: publication
title: Long45;form Video45;language Pre45;training With Multimodal Temporal Contrastive Learning
authors: Sun Yuchong, Xue Hongwei, Song Ruihua, Liu Bei, Yang Huan, Fu Jianlong
conference: "Arxiv"
year: 2022
bibkey: sun2022long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.06031"}
  - {name: "Code", url: "https://github.com/microsoft/XPretrain"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Large45;scale video45;language pre45;training has shown significant improvement in video45;language understanding tasks. Previous studies of video45;language pretraining mainly focus on short45;form videos (i.e. within 30 seconds) and sentences leaving long45;form video45;language pre45;training rarely explored. Directly learning representation from long45;form videos and language may benefit many long45;form video45;language understanding tasks. However it is challenging due to the difficulty of modeling long45;range relationships and the heavy computational burden caused by more frames. In this paper we introduce a Long45;Form VIdeo45;LAnguage pre45;training model (LF45;VILA) and train it on a large45;scale long45;form video and paragraph dataset constructed from an existing public dataset. To effectively capture the rich temporal dynamics and to better align video and language in an efficient end45;to45;end manner we introduce two novel designs in our LF45;VILA model. We first propose a Multimodal Temporal Contrastive (MTC) loss to learn the temporal relation across different modalities by encouraging fine45;grained alignment between long45;form videos and paragraphs. Second we propose a Hierarchical Temporal Window Attention (HTWA) mechanism to effectively capture long45;range dependency while reducing computational cost in Transformer. We fine45;tune the pre45;trained LF45;VILA model on seven downstream long45;form video45;language understanding tasks of paragraph45;to45;video retrieval and long45;form video question45;answering and achieve new state45;of45;the45;art performances. Specifically our model achieves 16.137; relative improvement on ActivityNet paragraph45;to45;video retrieval task and 2.437; on How2QA task respectively. We release our code dataset and pre45;trained models at https://github.com/microsoft/XPretrain.
