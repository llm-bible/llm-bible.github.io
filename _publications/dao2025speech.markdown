---
layout: publication
title: 'Speechless: Speech Instruction Training Without Speech For Low Resource Languages'
authors: Alan Gia Tuan Dao Dao, Dinh Bach Vu, Huy Hoang Ha, Tuan Le Duc Anh, Shreyas Gopal, Yue Heng Yeo, Warren Keng Hoong Low, Eng Siong Chng, Jia Qi Yip
conference: "Arxiv"
year: 2025
bibkey: dao2025speech
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17417"}
tags: ['Fine-Tuning', 'Tools', 'INTERSPEECH', 'Training Techniques', 'Pretraining Methods']
---
The rapid growth of voice assistants powered by large language models (LLM) has highlighted a need for speech instruction data to train these systems. Despite the abundance of speech recognition data, there is a notable scarcity of speech instruction data, which is essential for fine-tuning models to understand and execute spoken commands. Generating high-quality synthetic speech requires a good text-to-speech (TTS) model, which may not be available to low resource languages. Our novel approach addresses this challenge by halting synthesis at the semantic representation level, bypassing the need for TTS. We achieve this by aligning synthetic semantic representations with the pre-trained Whisper encoder, enabling an LLM to be fine-tuned on text instructions while maintaining the ability to understand spoken instructions during inference. This simplified training process is a promising approach to building voice assistant for low-resource languages.
