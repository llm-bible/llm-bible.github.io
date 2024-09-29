---
layout: publication
title: RALL45;E Robust Codec Language Modeling With Chain45;of45;thought Prompting For Text45;to45;speech Synthesis
authors: Xin Detai, Tan Xu, Shen Kai, Ju Zeqian, Yang Dongchao, Wang Yuancheng, Takamichi Shinnosuke, Saruwatari Hiroshi, Liu Shujie, Li Jinyu, Zhao Sheng
conference: "Arxiv"
year: 2024
bibkey: xin2024rall
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03204"}
tags: ['Attention Mechanism', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Security', 'Transformer']
---
We present RALL45;E a robust language modeling method for text45;to45;speech (TTS) synthesis. While previous work based on large language models (LLMs) shows impressive performance on zero45;shot TTS such methods often suffer from poor robustness such as unstable prosody (weird pitch and rhythm/duration) and a high word error rate (WER) due to the autoregressive prediction style of language models. The core idea behind RALL45;E is chain45;of45;thought (CoT) prompting which decomposes the task into simpler steps to enhance the robustness of LLM45;based TTS. To accomplish this idea RALL45;E first predicts prosody features (pitch and duration) of the input text and uses them as intermediate conditions to predict speech tokens in a CoT style. Second RALL45;E utilizes the predicted duration prompt to guide the computing of self45;attention weights in Transformer to enforce the model to focus on the corresponding phonemes and prosody features when predicting speech tokens. Results of comprehensive objective and subjective evaluations demonstrate that compared to a powerful baseline method VALL45;E RALL45;E significantly improves the WER of zero45;shot TTS from 5.637; (without reranking) and 1.737; (with reranking) to 2.537; and 1.037; respectively. Furthermore we demonstrate that RALL45;E correctly synthesizes sentences that are hard for VALL45;E and reduces the error rate from 6837; to 437;.
