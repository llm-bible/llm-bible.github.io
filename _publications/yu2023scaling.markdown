---
layout: publication
title: 'Scaling Autoregressive Multi-modal Models: Pretraining And Instruction Tuning'
authors: Lili Yu, Bowen Shi, Ramakanth Pasunuru, Benjamin Muller, Olga Golovneva, Tianlu Wang, Arun Babu, Binh Tang, Brian Karrer, Shelly Sheynin, Candace Ross, Adam Polyak, Russell Howes, Vasu Sharma, Puxin Xu, Hovhannes Tamoyan, Oron Ashual, Uriel Singer, Shang-wen Li, Susan Zhang, Richard James, Gargi Ghosh, Yaniv Taigman, Maryam Fazel-zarandi, Asli Celikyilmaz, Luke Zettlemoyer, Armen Aghajanyan
conference: "Arxiv"
year: 2023
bibkey: yu2023scaling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.02591'}
tags: ['Language Modeling', 'RAG', 'Training Techniques', 'GPT', 'Model Architecture', 'Fine-Tuning', 'Applications', 'Pre-Training', 'Pretraining Methods']
---
We present CM3Leon (pronounced "Chameleon"), a retrieval-augmented,
token-based, decoder-only multi-modal language model capable of generating and
infilling both text and images. CM3Leon uses the CM3 multi-modal architecture
but additionally shows the extreme benefits of scaling up and tuning on more
diverse instruction-style data. It is the first multi-modal model trained with
a recipe adapted from text-only language models, including a large-scale
retrieval-augmented pre-training stage and a second multi-task supervised
fine-tuning (SFT) stage. It is also a general-purpose model that can do both
text-to-image and image-to-text generation, allowing us to introduce
self-contained contrastive decoding methods that produce high-quality outputs.
Extensive experiments demonstrate that this recipe is highly effective for
multi-modal models. CM3Leon achieves state-of-the-art performance in
text-to-image generation with 5x less training compute than comparable methods
(zero-shot MS-COCO FID of 4.88). After SFT, CM3Leon can also demonstrate
unprecedented levels of controllability in tasks ranging from language-guided
image editing to image-controlled generation and segmentation.
