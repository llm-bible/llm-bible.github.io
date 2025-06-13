---
layout: publication
title: 'Simuls2s-llm: Unlocking Simultaneous Inference Of Speech Llms For Speech-to-speech Translation'
authors: Keqi Deng, Wenxi Chen, Xie Chen, Philip C. Woodland
conference: "Arxiv"
year: 2025
bibkey: deng2025unlocking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.15509'}
tags: ['Prompting', 'Training Techniques']
---
Simultaneous speech translation (SST) outputs translations in parallel with
streaming speech input, balancing translation quality and latency. While large
language models (LLMs) have been extended to handle the speech modality,
streaming remains challenging as speech is prepended as a prompt for the entire
generation process. To unlock LLM streaming capability, this paper proposes
SimulS2S-LLM, which trains speech LLMs offline and employs a test-time policy
to guide simultaneous inference. SimulS2S-LLM alleviates the mismatch between
training and inference by extracting boundary-aware speech prompts that allows
it to be better matched with text input data. SimulS2S-LLM achieves
simultaneous speech-to-speech translation (Simul-S2ST) by predicting discrete
output speech tokens and then synthesising output speech using a pre-trained
vocoder. An incremental beam search is designed to expand the search space of
speech token prediction without increasing latency. Experiments on the CVSS
speech data show that SimulS2S-LLM offers a better translation quality-latency
trade-off than existing methods that use the same training data, such as
improving ASR-BLEU scores by 3 points at similar latency.
