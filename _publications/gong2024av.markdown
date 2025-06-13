---
layout: publication
title: 'Av-odyssey Bench: Can Your Multimodal Llms Really Understand Audio-visual Information?'
authors: Kaixiong Gong, Kaituo Feng, Bohao Li, Yibing Wang, Mofan Cheng, Shijia Yang, Jiaming Han, Benyou Wang, Yutong Bai, Zhuoran Yang, Xiangyu Yue
conference: "Arxiv"
year: 2024
bibkey: gong2024av
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.02611"}
tags: ['Multimodal Models', 'Model Architecture', 'RAG', 'GPT', 'Applications']
---
Recently, multimodal large language models (MLLMs), such as GPT-4o, Gemini
1.5 Pro, and Reka Core, have expanded their capabilities to include vision and
audio modalities. While these models demonstrate impressive performance across
a wide range of audio-visual applications, our proposed DeafTest reveals that
MLLMs often struggle with simple tasks humans find trivial: 1) determining
which of two sounds is louder, and 2) determining which of two sounds has a
higher pitch. Motivated by these observations, we introduce AV-Odyssey Bench, a
comprehensive audio-visual benchmark designed to assess whether those MLLMs can
truly understand the audio-visual information. This benchmark encompasses 4,555
carefully crafted problems, each incorporating text, visual, and audio
components. To successfully infer answers, models must effectively leverage
clues from both visual and audio inputs. To ensure precise and objective
evaluation of MLLM responses, we have structured the questions as
multiple-choice, eliminating the need for human evaluation or LLM-assisted
assessment. We benchmark a series of closed-source and open-source models and
summarize the observations. By revealing the limitations of current models, we
aim to provide useful insight for future dataset collection and model
development.
