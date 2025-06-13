---
layout: publication
title: 'An Empirical Study Of Speech Language Models For Prompt-conditioned Speech Synthesis'
authors: Yifan Peng, Ilia Kulikov, Yilin Yang, Sravya Popuri, Hui Lu, Changhan Wang, Hongyu Gong
conference: "Arxiv"
year: 2024
bibkey: peng2024empirical
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.12402'}
tags: ['Prompting', 'In-Context Learning', 'GPT', 'Pretraining Methods']
---
Speech language models (LMs) are promising for high-quality speech synthesis
through in-context learning. A typical speech LM takes discrete semantic units
as content and a short utterance as prompt, and synthesizes speech which
preserves the content's semantics but mimics the prompt's style. However, there
is no systematic understanding on how the synthesized audio is controlled by
the prompt and content. In this work, we conduct an empirical study of the
widely used autoregressive (AR) and non-autoregressive (NAR) speech LMs and
provide insights into the prompt design and content semantic units. Our
analysis reveals that heterogeneous and nonstationary prompts hurt the audio
quality in contrast to the previous finding that longer prompts always lead to
better synthesis. Moreover, we find that the speaker style of the synthesized
audio is also affected by the content in addition to the prompt. We further
show that semantic units carry rich acoustic information such as pitch, tempo,
volume and speech emphasis, which might be leaked from the content to the
synthesized audio.
