---
layout: publication
title: Unified Vision-language Pre-training For Image Captioning And VQA
authors: Zhou Luowei, Palangi Hamid, Zhang Lei, Hu Houdong, Corso Jason J., Gao Jianfeng
conference: "Arxiv"
year: 2019
bibkey: zhou2019unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.11059"}
  - {name: "Code", url: "https://github.com/LuoweiZhou/VLP"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
This paper presents a unified Vision-Language Pre-training (VLP) model. The model is unified in that (1) it can be fine-tuned for either vision-language generation (e.g. image captioning) or understanding (e.g. visual question answering) tasks and (2) it uses a shared multi-layer transformer network for both encoding and decoding which differs from many existing methods where the encoder and decoder are implemented using separate models. The unified VLP model is pre-trained on a large amount of image-text pairs using the unsupervised learning objectives of two tasks bidirectional and sequence-to-sequence (seq2seq) masked vision-language prediction. The two tasks differ solely in what context the prediction conditions on. This is controlled by utilizing specific self-attention masks for the shared transformer network. To the best of our knowledge VLP is the first reported model that achieves state-of-the-art results on both vision-language generation and understanding tasks as disparate as image captioning and visual question answering across three challenging benchmark datasets COCO Captions Flickr30k Captions and VQA 2.0. The code and the pre-trained models are available at https://github.com/LuoweiZhou/VLP.
