---
layout: publication
title: Tackling VQA With Pretrained Foundation Models Without Further Training
authors: Tan Alvin De Jun, Shen Bingquan
conference: "Arxiv"
year: 2023
bibkey: tan2023tackling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.15487"}
tags: ['Applications', 'Training Techniques']
---
Large language models (LLMs) have achieved state45;of45;the45;art results in many natural language processing tasks. They have also demonstrated ability to adapt well to different tasks through zero45;shot or few45;shot settings. With the capability of these LLMs researchers have looked into how to adopt them for use with Visual Question Answering (VQA). Many methods require further training to align the image and text embeddings. However these methods are computationally expensive and requires large scale image45;text dataset for training. In this paper we explore a method of combining pretrained LLMs and other foundation models without further training to solve the VQA problem. The general idea is to use natural language to represent the images such that the LLM can understand the images. We explore different decoding strategies for generating textual representation of the image and evaluate their performance on the VQAv2 dataset.
