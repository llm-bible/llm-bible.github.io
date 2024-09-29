---
layout: publication
title: Integrating Paralinguistics In Speech45;empowered Large Language Models For Natural Conversation
authors: Kim Heeseung, Seo Soonshin, Jeong Kyeongseok, Kwon Ohsung, Kim Soyoon, Kim Jungwhan, Lee Jaehong, Song Eunwoo, Oh Myungwoo, Ha Jung-woo, Yoon Sungroh, Yoo Kang Min
conference: "Arxiv"
year: 2024
bibkey: kim2024integrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.05706"}
tags: ['Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Recent work shows promising results in expanding the capabilities of large language models (LLM) to directly understand and synthesize speech. However an LLM45;based strategy for modeling spoken dialogs remains elusive calling for further investigation. This paper introduces an extensive speech45;text LLM framework the Unified Spoken Dialog Model (USDM) designed to generate coherent spoken responses with naturally occurring prosodic features relevant to the given input speech without relying on explicit automatic speech recognition (ASR) or text45;to45;speech (TTS) systems. We have verified the inclusion of prosody in speech tokens that predominantly contain semantic information and have used this foundation to construct a prosody45;infused speech45;text model. Additionally we propose a generalized speech45;text pretraining scheme that enhances the capture of cross45;modal semantics. To construct USDM we fine45;tune our speech45;text model on spoken dialog data using a multi45;step spoken dialog template that stimulates the chain45;of45;reasoning capabilities exhibited by the underlying LLM. Automatic and human evaluations on the DailyTalk dataset demonstrate that our approach effectively generates natural45;sounding spoken responses surpassing previous and cascaded baselines. We will make our code and checkpoints publicly available.
