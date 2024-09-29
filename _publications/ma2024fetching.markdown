---
layout: publication
title: Clawmachine Fetching Visual Tokens As An Entity For Referring And Grounding
authors: Ma Tianren, Xie Lingxi, Tian Yunjie, Yang Boyu, Zhang Yuan, Doermann David, Ye Qixiang
conference: "Arxiv"
year: 2024
bibkey: ma2024fetching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11327"}
tags: ['Model Architecture', 'Multimodal Models', 'Prompting', 'Training Techniques']
---
An essential topic for multimodal large language models (MLLMs) is aligning vision and language concepts at a finer level. In particular we devote efforts to encoding visual referential information for tasks such as referring and grounding. Existing methods including proxy encoding and geometry encoding incorporate additional syntax to encode the objects location bringing extra burdens in training MLLMs to communicate between language and vision. This study presents ClawMachine offering a new methodology that notates an entity directly using the visual tokens. It allows us to unify the prompt and answer of visual referential tasks without additional syntax. Upon a joint vision-language vocabulary ClawMachine unifies visual referring and grounding into an auto-regressive format and learns with a decoder-only architecture. Experiments validate that our model achieves competitive performance across visual referring and grounding tasks with a reduced demand for training data. Additionally ClawMachine demonstrates a native ability to integrate multi-source information for complex visual reasoning which prior MLLMs can hardly perform without specific adaptions.
