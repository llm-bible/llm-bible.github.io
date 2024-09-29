---
layout: publication
title: Speech Reallm 45;45; Real45;time Streaming Speech Recognition With Multimodal Llms By Teaching The Flow Of Time
authors: Seide Frank, Doulaty Morrie, Shi Yangyang, Gaur Yashesh, Jia Junteng, Wu Chunyang
conference: "Arxiv"
year: 2024
bibkey: seide2024speech
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.09569"}
tags: ['Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Prompting']
---
We introduce Speech ReaLLM a new ASR architecture that marries decoder45;only ASR with the RNN45;T to make multimodal LLM architectures capable of real45;time streaming. This is the first decoder45;only ASR architecture designed to handle continuous audio without explicit end45;pointing. Speech ReaLLM is a special case of the more general ReaLLM (real45;time LLM) approach also introduced here for the first time. The idea is inspired by RNN45;T Instead of generating a response only at the end of a user prompt generate after every input token received in real time (it is often empty). On Librispeech test an 80M Speech ReaLLM achieves WERs of 3.037; and 7.437; in real time (without an external LM or auxiliary loss). This is only slightly above a 3x larger Attention45;Encoder45;Decoder baseline. We also show that this way an LLM architecture can learn to represent and reproduce the flow of time; and that a pre45;trained 7B LLM can be fine45;tuned to do reasonably well on this task.
