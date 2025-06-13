---
layout: publication
title: 'Glm-4-voice: Towards Intelligent And Human-like End-to-end Spoken Chatbot'
authors: Aohan Zeng, Zhengxiao Du, Mingdao Liu, Kedong Wang, Shengmin Jiang, Lei Zhao, Yuxiao Dong, Jie Tang
conference: "Arxiv"
year: 2024
bibkey: zeng2024glm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.02612"}
  - {name: "Code", url: "https://github.com/THUDM/GLM-4-Voice"}
  - {name: "Code", url: "https://huggingface.co/THUDM/glm-4-voice-9b"}
tags: ['INTERSPEECH', 'Pre-Training', 'Applications', 'Language Modeling', 'Reinforcement Learning', 'Training Techniques', 'Has Code']
---
We introduce GLM-4-Voice, an intelligent and human-like end-to-end spoken
chatbot. It supports both Chinese and English, engages in real-time voice
conversations, and varies vocal nuances such as emotion, intonation, speech
rate, and dialect according to user instructions. GLM-4-Voice uses an ultra-low
bitrate (175bps), single-codebook speech tokenizer with 12.5Hz frame rate
derived from an automatic speech recognition (ASR) model by incorporating a
vector-quantized bottleneck into the encoder. To efficiently transfer knowledge
from text to speech modalities, we synthesize speech-text interleaved data from
existing text pre-training corpora using a text-to-token model. We continue
pre-training from the pre-trained text language model GLM-4-9B with a
combination of unsupervised speech data, interleaved speech-text data, and
supervised speech-text data, scaling up to 1 trillion tokens, achieving
state-of-the-art performance in both speech language modeling and spoken
question answering. We then fine-tune the pre-trained model with high-quality
conversational speech data, achieving superior performance compared to existing
baselines in both conversational ability and speech quality. The open models
can be accessed through https://github.com/THUDM/GLM-4-Voice and
https://huggingface.co/THUDM/glm-4-voice-9b.
