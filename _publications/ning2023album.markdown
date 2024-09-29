---
layout: publication
title: Album Storytelling With Iterative Story45;aware Captioning And Large Language Models
authors: Ning Munan, Xie Yujia, Chen Dongdong, Song Zeyin, Yuan Lu, Tian Yonghong, Ye Qixiang, Yuan Li
conference: "Arxiv"
year: 2023
bibkey: ning2023album
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12943"}
tags: ['Pretraining Methods', 'Reinforcement Learning']
---
This work studies how to transform an album to vivid and coherent stories a task we refer to as album storytelling. While this task can help preserve memories and facilitate experience sharing it remains an underexplored area in current literature. With recent advances in Large Language Models (LLMs) it is now possible to generate lengthy coherent text opening up the opportunity to develop an AI assistant for album storytelling. One natural approach is to use caption models to describe each photo in the album and then use LLMs to summarize and rewrite the generated captions into an engaging story. However we find this often results in stories containing hallucinated information that contradicts the images as each generated caption (story45;agnostic) is not always about the description related to the whole story or miss some necessary information. To address these limitations we propose a new iterative album storytelling pipeline. Specifically we start with an initial story and build a story45;aware caption model to refine the captions using the whole story as guidance. The polished captions are then fed into the LLMs to generate a new refined story. This process is repeated iteratively until the story contains minimal factual errors while maintaining coherence. To evaluate our proposed pipeline we introduce a new dataset of image collections from vlogs and a set of systematic evaluation metrics. Our results demonstrate that our method effectively generates more accurate and engaging stories for albums with enhanced coherence and vividness.
