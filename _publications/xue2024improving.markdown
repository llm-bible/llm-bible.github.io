---
layout: publication
title: 'Improving Audio Codec-based Zero-shot Text-to-speech Synthesis With Multi-modal Context And Large Language Model'
authors: Xue Jinlong, Deng Yayue, Han Yicheng, Gao Yingming, Li Ya
conference: "Arxiv"
year: 2024
bibkey: xue2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03706"}
tags: ['Prompting', 'RAG', 'Reinforcement Learning', 'Uncategorized']
---
Recent advances in large language models (LLMs) and development of audio
codecs greatly propel the zero-shot TTS. They can synthesize personalized
speech with only a 3-second speech of an unseen speaker as acoustic prompt.
However, they only support short speech prompts and cannot leverage longer
context information, as required in audiobook and conversational TTS scenarios.
In this paper, we introduce a novel audio codec-based TTS model to adapt
context features with multiple enhancements. Inspired by the success of
Qformer, we propose a multi-modal context-enhanced Qformer (MMCE-Qformer) to
utilize additional multi-modal context information. Besides, we adapt a
pretrained LLM to leverage its understanding ability to predict semantic
tokens, and use a SoundStorm to generate acoustic tokens thereby enhancing
audio quality and speaker similarity. The extensive objective and subjective
evaluations show that our proposed method outperforms baselines across various
context TTS scenarios.
