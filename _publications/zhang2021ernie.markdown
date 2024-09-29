---
layout: publication
title: Ernie45;vilg Unified Generative Pre45;training For Bidirectional Vision45;language Generation
authors: Zhang Han, Yin Weichong, Fang Yewei, Li Lanxin, Duan Boqiang, Wu Zhihua, Sun Yu, Tian Hao, Wu Hua, Wang Haifeng
conference: "Arxiv"
year: 2021
bibkey: zhang2021ernie
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.15283"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Tools', 'Training Techniques', 'Transformer']
---
Conventional methods for the image45;text generation tasks mainly tackle the naturally bidirectional generation tasks separately focusing on designing task45;specific frameworks to improve the quality and fidelity of the generated samples. Recently Vision45;Language Pre45;training models have greatly improved the performance of the image45;to45;text generation tasks but large45;scale pre45;training models for text45;to45;image synthesis task are still under45;developed. In this paper we propose ERNIE45;ViLG a unified generative pre45;training framework for bidirectional image45;text generation with transformer model. Based on the image quantization models we formulate both image generation and text generation as autoregressive generative tasks conditioned on the text/image input. The bidirectional image45;text generative modeling eases the semantic alignments across vision and language. For the text45;to45;image generation process we further propose an end45;to45;end training method to jointly learn the visual sequence generator and the image reconstructor. To explore the landscape of large45;scale pre45;training for bidirectional text45;image generation we train a 1045;billion parameter ERNIE45;ViLG model on a large45;scale dataset of 145 million (Chinese) image45;text pairs which achieves state45;of45;the45;art performance for both text45;to45;image and image45;to45;text tasks obtaining an FID of 7.9 on MS45;COCO for text45;to45;image synthesis and best results on COCO45;CN and AIC45;ICC for image captioning.
