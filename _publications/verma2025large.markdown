---
layout: publication
title: 'Large Language Models Implicitly Learn To See And Hear Just By Reading'
authors: Prateek Verma, Mert Pilanci
conference: "Arxiv"
year: 2025
bibkey: verma2025large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17091"}
tags: ['Training Techniques', 'Applications', 'Model Architecture']
---
This paper presents a fascinating find: By training an auto-regressive LLM model on text tokens, the text model inherently develops internally an ability to understand images and audio, thereby developing the ability to see and hear just by reading. Popular audio and visual LLM models fine-tune text LLM models to give text output conditioned on images and audio embeddings. On the other hand, our architecture takes in patches of images, audio waveforms or tokens as input. It gives us the embeddings or category labels typical of a classification pipeline. We show the generality of text weights in aiding audio classification for datasets FSD-50K and GTZAN. Further, we show this working for image classification on CIFAR-10 and Fashion-MNIST, as well on image patches. This pushes the notion of text-LLMs learning powerful internal circuits that can be utilized by activating necessary connections for various applications rather than training models from scratch every single time.
