---
layout: publication
title: Style45;talker Finetuning Audio Language Model And Style45;based Text45;to45;speech Model For Fast Spoken Dialogue Generation
authors: Li Yinghao Aaron, Jiang Xilin, Darefsky Jordan, Zhu Ge, Mesgarani Nima
conference: "Arxiv"
year: 2024
bibkey: li2024style
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11849"}
tags: ['Applications', 'Pretraining Methods', 'Tools']
---
The rapid advancement of large language models (LLMs) has significantly propelled the development of text45;based chatbots demonstrating their capability to engage in coherent and contextually relevant dialogues. However extending these advancements to enable end45;to45;end speech45;to45;speech conversation bots remains a formidable challenge primarily due to the extensive dataset and computational resources required. The conventional approach of cascading automatic speech recognition (ASR) LLM and text45;to45;speech (TTS) models in a pipeline while effective suffers from unnatural prosody because it lacks direct interactions between the input audio and its transcribed text and the output audio. These systems are also limited by their inherent latency from the ASR process for real45;time applications. This paper introduces Style45;Talker an innovative framework that fine45;tunes an audio LLM alongside a style45;based TTS model for fast spoken dialog generation. Style45;Talker takes user input audio and uses transcribed chat history and speech styles to generate both the speaking style and text for the response. Subsequently the TTS model synthesizes the speech which is then played back to the user. While the response speech is being played the input speech undergoes ASR processing to extract the transcription and speaking style serving as the context for the ensuing dialogue turn. This novel pipeline accelerates the traditional cascade ASR45;LLM45;TTS systems while integrating rich paralinguistic information from input speech. Our experimental results show that Style45;Talker significantly outperforms the conventional cascade and speech45;to45;speech baselines in terms of both dialogue naturalness and coherence while being more than 5037; faster.
