---
layout: publication
title: 'Panther: Illuminate The Sight Of Multimodal Llms With Instruction-guided Visual Prompts'
authors: Honglin Li, Yuting Gao, Chenglu Zhu, Jingdong Chen, Ming Yang, Lin Yang
conference: "Arxiv"
year: 2024
bibkey: li2024illuminate
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.13909'}
tags: ['Model Architecture', 'Tools', 'Training Techniques', 'Prompting', 'Multimodal Models', 'Reinforcement Learning']
---
Multimodal large language models (MLLMs) are closing the gap to human visual
perception capability rapidly, while, still lag behind on attending to subtle
images details or locating small objects precisely, etc. Common schemes to
tackle these issues include deploying multiple vision encoders or operating on
original high-resolution images. Few studies have concentrated on taking the
textual instruction into improving visual representation, resulting in losing
focus in some vision-centric tasks, a phenomenon we herein termed as Amblyopia.
In this work, we introduce Panther, a MLLM that closely adheres to user
instruction and locates targets of interests precisely, with the finesse of a
black panther. Specifically, Panther comprises three integral components:
Panther-VE, Panther-Bridge, and Panther-Decoder. Panther-VE integrates user
instruction information at the early stages of the vision encoder, thereby
extracting the most relevant and useful visual representations. The
Panther-Bridge module, equipped with powerful filtering capabilities,
significantly reduces redundant visual information, leading to a substantial
savings in training costs. The Panther-Decoder is versatile and can be employed
with any decoder-only architecture of LLMs without discrimination. Experimental
results, particularly on vision-centric benchmarks, have demonstrated the
effectiveness of Panther.
