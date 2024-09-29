---
layout: publication
title: Llama45;omni Seamless Speech Interaction With Large Language Models
authors: Fang Qingkai, Guo Shoutao, Zhou Yan, Ma Zhengrui, Zhang Shaolei, Feng Yang
conference: "Arxiv"
year: 2024
bibkey: fang2024llama
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.06666"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Training Techniques']
---
Models like GPT45;4o enable real45;time interaction with large language models (LLMs) through speech significantly enhancing user experience compared to traditional text45;based interaction. However there is still a lack of exploration on how to build speech interaction models based on open45;source LLMs. To address this we propose LLaMA45;Omni a novel model architecture designed for low45;latency and high45;quality speech interaction with LLMs. LLaMA45;Omni integrates a pretrained speech encoder a speech adaptor an LLM and a streaming speech decoder. It eliminates the need for speech transcription and can simultaneously generate text and speech responses directly from speech instructions with extremely low latency. We build our model based on the latest Llama45;3.145;8B45;Instruct model. To align the model with speech interaction scenarios we construct a dataset named InstructS2S45;200K which includes 200K speech instructions and corresponding speech responses. Experimental results show that compared to previous speech45;language models LLaMA45;Omni provides better responses in both content and style with a response latency as low as 226ms. Additionally training LLaMA45;Omni takes less than 3 days on just 4 GPUs paving the way for the efficient development of speech45;language models in the future.
