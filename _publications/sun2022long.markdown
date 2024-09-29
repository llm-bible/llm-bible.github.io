---
layout: publication
title: Long-form Video-language Pre-training With Multimodal Temporal Contrastive Learning
authors: Sun Yuchong, Xue Hongwei, Song Ruihua, Liu Bei, Yang Huan, Fu Jianlong
conference: "Arxiv"
year: 2022
bibkey: sun2022long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.06031"}
  - {name: "Code", url: "https://github.com/microsoft/XPretrain"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Large-scale video-language pre-training has shown significant improvement in video-language understanding tasks. Previous studies of video-language pretraining mainly focus on short-form videos (i.e. within 30 seconds) and sentences leaving long-form video-language pre-training rarely explored. Directly learning representation from long-form videos and language may benefit many long-form video-language understanding tasks. However it is challenging due to the difficulty of modeling long-range relationships and the heavy computational burden caused by more frames. In this paper we introduce a Long-Form VIdeo-LAnguage pre-training model (LF-VILA) and train it on a large-scale long-form video and paragraph dataset constructed from an existing public dataset. To effectively capture the rich temporal dynamics and to better align video and language in an efficient end-to-end manner we introduce two novel designs in our LF-VILA model. We first propose a Multimodal Temporal Contrastive (MTC) loss to learn the temporal relation across different modalities by encouraging fine-grained alignment between long-form videos and paragraphs. Second we propose a Hierarchical Temporal Window Attention (HTWA) mechanism to effectively capture long-range dependency while reducing computational cost in Transformer. We fine-tune the pre-trained LF-VILA model on seven downstream long-form video-language understanding tasks of paragraph-to-video retrieval and long-form video question-answering and achieve new state-of-the-art performances. Specifically our model achieves 16.137; relative improvement on ActivityNet paragraph-to-video retrieval task and 2.437; on How2QA task respectively. We release our code dataset and pre-trained models at https://github.com/microsoft/XPretrain."
