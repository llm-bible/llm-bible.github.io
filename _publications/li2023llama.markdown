---
layout: publication
title: 'Llama-vid: An Image Is Worth 2 Tokens In Large Language Models'
authors: Yanwei Li, Chengyao Wang, Jiaya Jia
conference: Arxiv
year: 2023
citations: 22
bibkey: li2023llama
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.17043'}, {name: Code,
    url: 'https://github.com/dvlab-research/LLaMA-VID}{https://github.com/dvlab-research/LLaMA-VID'}]
tags: [Tools, Reinforcement Learning, Multimodal Models]
---
In this work, we present a novel method to tackle the token generation
challenge in Vision Language Models (VLMs) for video and image understanding,
called LLaMA-VID. Current VLMs, while proficient in tasks like image captioning
and visual question answering, face computational burdens when processing long
videos due to the excessive visual tokens. LLaMA-VID addresses this issue by
representing each frame with two distinct tokens, namely context token and
content token. The context token encodes the overall image context based on
user input, whereas the content token encapsulates visual cues in each frame.
This dual-token strategy significantly reduces the overload of long videos
while preserving critical information. Generally, LLaMA-VID empowers existing
frameworks to support hour-long videos and pushes their upper limit with an
extra context token. It is proved to surpass previous methods on most of video-
or image-based benchmarks. Code is available
https://github.com/dvlab-research/LLaMA-VID\}\{https://github.com/dvlab-research/LLaMA-VID