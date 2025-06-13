---
layout: publication
title: 'Mounting Video Metadata On Transformer-based Language Model For Open-ended Video Question Answering'
authors: Donggeon Lee, Seongho Choi, Youwon Jang, Byoung-tak Zhang
conference: "Arxiv"
year: 2021
bibkey: lee2021mounting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2108.05158"}
tags: ['Transformer', 'GPT', 'Applications', 'Model Architecture', 'Attention Mechanism', 'Pretraining Methods', 'Multimodal Models']
---
Video question answering has recently received a lot of attention from
multimodal video researchers. Most video question answering datasets are
usually in the form of multiple-choice. But, the model for the multiple-choice
task does not infer the answer. Rather it compares the answer candidates for
picking the correct answer. Furthermore, it makes it difficult to extend to
other tasks. In this paper, we challenge the existing multiple-choice video
question answering by changing it to open-ended video question answering. To
tackle open-ended question answering, we use the pretrained GPT2 model. The
model is fine-tuned with video inputs and subtitles. An ablation study is
performed by changing the existing DramaQA dataset to an open-ended question
answering, and it shows that performance can be improved using video metadata.
