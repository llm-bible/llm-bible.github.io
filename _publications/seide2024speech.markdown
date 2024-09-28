---
layout: publication
title: Speech ReaLLM -- Real-time Streaming Speech Recognition with Multimodal LLMs by Teaching the Flow of Time
authors: Seide Frank, Doulaty Morrie, Shi Yangyang, Gaur Yashesh, Jia Junteng, Wu Chunyang
conference: "Arxiv"
year: 2024
bibkey: seide2024speech
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.09569"}
tags: ['ARXIV', 'Attention Mechanism', 'LLM', 'Multimodal Models', 'Prompt']
---
We introduce Speech ReaLLM a new ASR architecture that marries decoder-only ASR with the RNN-T to make multimodal LLM architectures capable of real-time streaming. This is the first decoder-only ASR architecture designed to handle continuous audio without explicit end-pointing. Speech ReaLLM is a special case of the more general ReaLLM (real-time LLM) approach also introduced here for the first time. The idea is inspired by RNN-T Instead of generating a response only at the end of a user prompt generate after every input token received in real time (it is often empty). On Librispeech test an 80M Speech ReaLLM achieves WERs of 3.0 and 7.4 in real time (without an external LM or auxiliary loss). This is only slightly above a 3x larger Attention-Encoder-Decoder baseline. We also show that this way an LLM architecture can learn to represent and reproduce the flow of time; and that a pre-trained 7B LLM can be fine-tuned to do reasonably well on this task.
