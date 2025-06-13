---
layout: publication
title: 'Touchtts: An Embarrassingly Simple TTS Framework That Everyone Can Touch'
authors: Xingchen Song, Mengtao Xing, Changwei Ma, Shengqiang Li, Di Wu, Binbin Zhang, Fuping Pan, Dinghao Zhou, Yuekai Zhang, Shun Lei, Zhendong Peng, Zhiyong Wu
conference: "Arxiv"
year: 2024
bibkey: song2024embarrassingly
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.08237'}
tags: ['Training Techniques', 'RAG', 'Tools', 'Model Architecture']
---
It is well known that LLM-based systems are data-hungry. Recent LLM-based TTS
works typically employ complex data processing pipelines to obtain high-quality
training data. These sophisticated pipelines require excellent models at each
stage (e.g., speech denoising, speech enhancement, speaker diarization, and
punctuation models), which themselves demand high-quality training data and are
rarely open-sourced. Even with state-of-the-art models, issues persist, such as
incomplete background noise removal and misalignment between punctuation and
actual speech pauses. Moreover, the stringent filtering strategies often retain
only 10-30% of the original data, significantly impeding data scaling efforts.
In this work, we leverage a noise-robust audio tokenizer (S3Tokenizer) to
design a simplified yet effective TTS data processing pipeline that maintains
data quality while substantially reducing data acquisition costs, achieving a
data retention rate of over 50%. Beyond data scaling challenges, LLM-based TTS
systems also incur higher deployment costs compared to conventional approaches.
Current systems typically use LLMs solely for text-to-token generation, while
requiring separate models (e.g., flow matching models) for token-to-waveform
generation, which cannot be directly executed by LLM inference engines, further
complicating deployment. To address these challenges, we eliminate redundant
modules in both LLM and flow components, replacing the flow model backbone with
an LLM architecture. Building upon this simplified flow backbone, we propose a
unified architecture for both streaming and non-streaming inference,
significantly reducing deployment costs. Finally, we explore the feasibility of
unifying TTS and ASR tasks using the same data for training, thanks to the
simplified pipeline and the S3Tokenizer that reduces the quality requirements
for TTS training data.
