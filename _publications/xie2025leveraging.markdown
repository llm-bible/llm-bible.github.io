---
layout: publication
title: 'Leveraging Chain Of Thought Towards Empathetic Spoken Dialogue Without Corresponding Question-answering Data'
authors: Jingran Xie, Shun Lei, Yue Yu, Yang Xiang, Hui Wang, Xixin Wu, Zhiyong Wu
conference: "Arxiv"
year: 2025
bibkey: xie2025leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.10937"}
tags: ['Fine-Tuning', 'RAG', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models', 'Prompting']
---
Empathetic dialogue is crucial for natural human-computer interaction,
allowing the dialogue system to respond in a more personalized and emotionally
aware manner, improving user satisfaction and engagement. The emergence of
large language models (LLMs) has revolutionized dialogue generation by
harnessing their powerful capabilities and shown its potential in multimodal
domains. Many studies have integrated speech with text-based LLMs to take
speech question as input and output text response. However, the lack of spoken
question-answering datasets that include speech style information to supervised
fine-tuning (SFT) limits the performance of these systems. As a result, while
these systems excel at understanding speech content, they often struggle to
generate empathetic responses. In response, we propose a novel approach that
circumvents the need for question-answering data, called Listen, Perceive, and
Express (LPE). Our method employs a two-stage training process, initially
guiding the LLM to listen the content and perceive the emotional aspects of
speech. Subsequently, we utilize Chain-of-Thought (CoT) prompting to unlock the
model's potential for expressing empathetic responses based on listened spoken
content and perceived emotional cues. We employ experiments to prove the
effectiveness of proposed method. To our knowledge, this is the first attempt
to leverage CoT for speech-based dialogue.
