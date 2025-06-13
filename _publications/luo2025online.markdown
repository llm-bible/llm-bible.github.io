---
layout: publication
title: 'Omniresponse: Online Multimodal Conversational Response Generation In Dyadic Interactions'
authors: Cheng Luo, Jianghui Wang, Bing Li, Siyang Song, Bernard Ghanem
conference: "Arxiv"
year: 2025
bibkey: luo2025online
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21724"}
tags: ['Multimodal Models', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods']
---
In this paper, we introduce Online Multimodal Conversational Response Generation (OMCRG), a novel task that aims to online generate synchronized verbal and non-verbal listener feedback, conditioned on the speaker's multimodal input. OMCRG reflects natural dyadic interactions and poses new challenges in achieving synchronization between the generated audio and facial responses of the listener. To address these challenges, we innovatively introduce text as an intermediate modality to bridge the audio and facial responses. We hence propose OmniResponse, a Multimodal Large Language Model (MLLM) that autoregressively generates high-quality multi-modal listener responses. OmniResponse leverages a pretrained LLM enhanced with two novel components: Chrono-Text, which temporally anchors generated text tokens, and TempoVoice, a controllable online TTS module that produces speech synchronized with facial reactions. To support further OMCRG research, we present ResponseNet, a new dataset comprising 696 high-quality dyadic interactions featuring synchronized split-screen videos, multichannel audio, transcripts, and facial behavior annotations. Comprehensive evaluations conducted on ResponseNet demonstrate that OmniResponse significantly outperforms baseline models in terms of semantic speech content, audio-visual synchronization, and generation quality.
