---
layout: publication
title: Language Models With Image Descriptors Are Strong Few45;shot Video45;language Learners
authors: Wang Zhenhailong, Li Manling, Xu Ruochen, Zhou Luowei, Lei Jie, Lin Xudong, Wang Shuohang, Yang Ziyi, Zhu Chenguang, Hoiem Derek, Chang Shih-fu, Bansal Mohit, Ji Heng
conference: "Arxiv"
year: 2022
bibkey: wang2022language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.10747"}
  - {name: "Code", url: "https://github.com/MikeWangWZHL/VidIL"}
tags: ['Applications', 'Has Code', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
The goal of this work is to build flexible video45;language models that can generalize to various video45;to45;text tasks from few examples such as domain45;specific captioning question answering and future event prediction. Existing few45;shot video45;language learners focus exclusively on the encoder resulting in the absence of a video45;to45;text decoder to handle generative tasks. Video captioners have been pretrained on large45;scale video45;language datasets but they rely heavily on finetuning and lack the ability to generate text for unseen tasks in a few45;shot setting. We propose VidIL a few45;shot Video45;language Learner via Image and Language models which demonstrates strong performance on few45;shot video45;to45;text tasks without the necessity of pretraining or finetuning on any video datasets. We use the image45;language models to translate the video content into frame captions object attribute and event phrases and compose them into a temporal structure template. We then instruct a language model with a prompt containing a few in45;context examples to generate a target output from the composed content. The flexibility of prompting allows the model to capture any form of text input such as automatic speech recognition (ASR) transcripts. Our experiments demonstrate the power of language models in understanding videos on a wide variety of video45;language tasks including video captioning video question answering video caption retrieval and video future event prediction. Especially on video future event prediction our few45;shot model significantly outperforms state45;of45;the45;art supervised models trained on large45;scale video datasets. Code and resources are publicly available for research purposes at https://github.com/MikeWangWZHL/VidIL .
