---
layout: publication
title: RALL-E\: Robust Codec Language Modeling With Chain-of-thought Prompting For Text-to-speech Synthesis
authors: Xin Detai, Tan Xu, Shen Kai, Ju Zeqian, Yang Dongchao, Wang Yuancheng, Takamichi Shinnosuke, Saruwatari Hiroshi, Liu Shujie, Li Jinyu, Zhao Sheng
conference: "Arxiv"
year: 2024
bibkey: xin2024rall
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03204"}
tags: ['Attention Mechanism', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Security', 'Transformer']
---
We present RALL-E a robust language modeling method for text-to-speech (TTS) synthesis. While previous work based on large language models (LLMs) shows impressive performance on zero-shot TTS such methods often suffer from poor robustness such as unstable prosody (weird pitch and rhythm/duration) and a high word error rate (WER) due to the autoregressive prediction style of language models. The core idea behind RALL-E is chain-of-thought (CoT) prompting which decomposes the task into simpler steps to enhance the robustness of LLM-based TTS. To accomplish this idea RALL-E first predicts prosody features (pitch and duration) of the input text and uses them as intermediate conditions to predict speech tokens in a CoT style. Second RALL-E utilizes the predicted duration prompt to guide the computing of self-attention weights in Transformer to enforce the model to focus on the corresponding phonemes and prosody features when predicting speech tokens. Results of comprehensive objective and subjective evaluations demonstrate that compared to a powerful baseline method VALL-E RALL-E significantly improves the WER of zero-shot TTS from 5.637; (without reranking) and 1.737; (with reranking) to 2.537; and 1.037; respectively. Furthermore we demonstrate that RALL-E correctly synthesizes sentences that are hard for VALL-E and reduces the error rate from 6837; to 437;.
