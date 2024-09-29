---
layout: publication
title: ELLA45;V Stable Neural Codec Language Modeling With Alignment45;guided Sequence Reordering
authors: Song Yakun, Chen Zhuo, Wang Xiaofei, Ma Ziyang, Chen Xie
conference: "Arxiv"
year: 2024
bibkey: song2024ella
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.07333"}
  - {name: "Code", url: "https://ereboas.github.io/ELLAV/"}
tags: ['GPT', 'Has Code', 'Language Modeling', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools']
---
The language model (LM) approach based on acoustic and linguistic prompts such as VALL45;E has achieved remarkable progress in the field of zero45;shot audio generation. However existing methods still have some limitations 1) repetitions transpositions and omissions in the output synthesized speech due to limited alignment constraints between audio and phoneme tokens; 2) challenges of fine45;grained control over the synthesized speech with autoregressive (AR) language model; 3) infinite silence generation due to the nature of AR45;based decoding especially under the greedy strategy. To alleviate these issues we propose ELLA45;V a simple but efficient LM45;based zero45;shot text45;to45;speech (TTS) framework which enables fine45;grained control over synthesized audio at the phoneme level. The key to ELLA45;V is interleaving sequences of acoustic and phoneme tokens where phoneme tokens appear ahead of the corresponding acoustic tokens. The experimental findings reveal that our model outperforms VALL45;E in terms of accuracy and delivers more stable results using both greedy and sampling45;based decoding strategies. The code of ELLA45;V will be open45;sourced after cleanups. Audio samples are available at https://ereboas.github.io/ELLAV/.
