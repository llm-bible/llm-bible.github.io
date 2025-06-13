---
layout: publication
title: 'Recent Advances In Speech Language Models: A Survey'
authors: Wenqian Cui, Dianzhi Yu, Xiaoqi Jiao, Ziqiao Meng, Guangyan Zhang, Qichao Wang, Yiwen Guo, Irwin King
conference: "Arxiv"
year: 2024
bibkey: cui2024recent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.03751"}
  - {name: "Code", url: "https://github.com/dreamtheater123/Awesome-SpeechLM-Survey"}
tags: ['INTERSPEECH', 'Tools', 'Survey Paper', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code']
---
Large Language Models (LLMs) have recently garnered significant attention,
primarily for their capabilities in text-based interactions. However, natural
human interaction often relies on speech, necessitating a shift towards
voice-based models. A straightforward approach to achieve this involves a
pipeline of ``Automatic Speech Recognition (ASR) + LLM + Text-to-Speech (TTS)",
where input speech is transcribed to text, processed by an LLM, and then
converted back to speech. Despite being straightforward, this method suffers
from inherent limitations, such as information loss during modality conversion,
significant latency due to the complex pipeline, and error accumulation across
the three stages. To address these issues, Speech Language Models (SpeechLMs)
-- end-to-end models that generate speech without converting from text -- have
emerged as a promising alternative. This survey paper provides the first
comprehensive overview of recent methodologies for constructing SpeechLMs,
detailing the key components of their architecture and the various training
recipes integral to their development. Additionally, we systematically survey
the various capabilities of SpeechLMs, categorize their evaluation metrics, and
discuss the challenges and future research directions in this rapidly evolving
field. The GitHub repository is available at
https://github.com/dreamtheater123/Awesome-SpeechLM-Survey
