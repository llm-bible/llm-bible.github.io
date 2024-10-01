---
layout: publication
title: 'Multiple-question Multiple-answer Text-vqa'
authors: Tang Peng, Appalaraju Srikar, Manmatha R., Xie Yusheng, Mahadevan Vijay
conference: "Arxiv"
year: 2023
bibkey: tang2023multiple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08622"}
tags: ['Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
"We present Multiple-Question Multiple-Answer (MQMA), a novel approach to do text-VQA in encoder-decoder transformer models. The text-VQA task requires a model to answer a question by understanding multi-modal content: text (typically from OCR) and an associated image. To the best of our knowledge, almost all previous approaches for text-VQA process a single question and its associated content to predict a single answer. In order to answer multiple questions from the same image, each question and content are fed into the model multiple times. In contrast, our proposed MQMA approach takes multiple questions and content as input at the encoder and predicts multiple answers at the decoder in an auto-regressive manner at the same time. We make several novel architectural modifications to standard encoder-decoder transformers to support MQMA. We also propose a novel MQMA denoising pre-training task which is designed to teach the model to align and delineate multiple questions and content with associated answers. MQMA pre-trained model achieves state-of-the-art results on multiple text-VQA datasets, each with strong baselines. Specifically, on OCR-VQA (+2.5&#37;), TextVQA (+1.4&#37;), ST-VQA (+0.6&#37;), DocVQA (+1.1&#37;) absolute improvements over the previous state-of-the-art approaches."
