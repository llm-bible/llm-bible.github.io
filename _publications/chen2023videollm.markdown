---
layout: publication
title: VideoLLM Modeling Video Sequence with Large Language Models
authors: Chen Guo, Zheng Yin-dong, Wang Jiahao, Xu Jilan, Huang Yifei, Pan Junting, Wang Yi, Wang Yali, Qiao Yu, Lu Tong, Wang Limin
conference: "Arxiv"
year: 2023
bibkey: chen2023videollm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13292"}
  - {name: "Code", url: "https://github.com/cg1177/VideoLLM"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
With the exponential growth of video data there is an urgent need for automated technology to analyze and comprehend video content. However existing video understanding models are often task-specific and lack a comprehensive capability of handling diverse tasks. The success of large language models (LLMs) like GPT has demonstrated their impressive abilities in sequence causal reasoning. Building upon this insight we propose a novel framework called VideoLLM that leverages the sequence reasoning capabilities of pre-trained LLMs from natural language processing (NLP) for video sequence understanding. VideoLLM incorporates a carefully designed Modality Encoder and Semantic Translator which convert inputs from various modalities into a unified token sequence. This token sequence is then fed into a decoder-only LLM. Subsequently with the aid of a simple task head our VideoLLM yields an effective unified framework for different kinds of video understanding tasks. To evaluate the efficacy of VideoLLM we conduct extensive experiments using multiple LLMs and fine-tuning methods. We evaluate our VideoLLM on eight tasks sourced from four different datasets. The experimental results demonstrate that the understanding and reasoning capabilities of LLMs can be effectively transferred to video understanding tasks. We release the code at https://github.com/cg1177/VideoLLM.
