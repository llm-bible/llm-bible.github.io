---
layout: publication
title: Lauragpt Listen Attend Understand And Regenerate Audio With GPT
authors: Du Zhihao, Wang Jiaming, Chen Qian, Chu Yunfei, Gao Zhifu, Li Zerui, Hu Kai, Zhou Xiaohuan, Xu Jin, Ma Ziyang, Wang Wen, Zheng Siqi, Zhou Chang, Yan Zhijie, Zhang Shiliang
conference: "Arxiv"
year: 2023
bibkey: du2023regenerate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.04673"}
tags: ['GPT', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Transformer']
---
Generative Pre45;trained Transformer (GPT) models have achieved remarkable performance on various natural language processing tasks and have shown great potential as backbones for audio45;and45;text large language models (LLMs). Previous mainstream audio45;and45;text LLMs use discrete audio tokens to represent both input and output audio; however they suffer from performance degradation on tasks such as automatic speech recognition speech45;to45;text translation and speech enhancement over models using continuous speech features. In this paper we propose LauraGPT a novel unified audio45;and45;text GPT45;based LLM for audio recognition understanding and generation. LauraGPT is a versatile LLM that can process both audio and text inputs and generate outputs in either modalities. We propose a novel data representation that combines continuous and discrete features for audio LauraGPT encodes input audio into continuous representations using an audio encoder and generates output audio from discrete codec codes. We propose a one45;step codec vocoder to overcome the prediction challenge caused by the multimodal distribution of codec tokens. We fine45;tune LauraGPT using supervised multi45;task learning. Extensive experiments show that LauraGPT consistently achieves comparable to superior performance compared to strong baselines on a wide range of audio tasks related to content semantics paralinguistics and audio45;signal analysis such as automatic speech recognition speech45;to45;text translation text45;to45;speech synthesis speech enhancement automated audio captioning speech emotion recognition and spoken language understanding.
