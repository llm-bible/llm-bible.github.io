---
layout: publication
title: Retrieval45;augmented Multimodal Language Modeling
authors: Yasunaga Michihiro, Aghajanyan Armen, Shi Weijia, James Rich, Leskovec Jure, Liang Percy, Lewis Mike, Zettlemoyer Luke, Yih Wen-tau
conference: "Arxiv"
year: 2022
bibkey: yasunaga2022retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.12561"}
tags: ['Applications', 'Language Modeling', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Recent multimodal models such as DALL45;E and CM3 have achieved remarkable progress in text45;to45;image and image45;to45;text generation. However these models store all learned knowledge (e.g. the appearance of the Eiffel Tower) in the model parameters requiring increasingly larger models and training data to capture more knowledge. To integrate knowledge in a more scalable and modular way we propose a retrieval45;augmented multimodal model which enables a base multimodal model (generator) to refer to relevant text and images fetched by a retriever from external memory (e.g. documents on the web). Specifically for the retriever we use a pretrained CLIP and for the generator we train a CM3 Transformer on the LAION dataset. Our resulting model named Retrieval45;Augmented CM3 (RA45;CM3) is the first multimodal model that can retrieve and generate both text and images. We show that RA45;CM3 significantly outperforms baseline multimodal models such as DALL45;E and CM3 on both image and caption generation tasks (12 FID and 17 CIDEr improvements on MS45;COCO) while requiring much less compute for training (<3037; of DALL45;E). Moreover we show that RA45;CM3 exhibits novel capabilities such as faithful image generation and multimodal in45;context learning (e.g. image generation from demonstrations).
