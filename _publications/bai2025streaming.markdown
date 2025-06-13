---
layout: publication
title: 'Speakstream: Streaming Text-to-speech With Interleaved Data'
authors: Richard He Bai, Zijin Gu, Tatiana Likhomanenko, Navdeep Jaitly
conference: "Arxiv"
year: 2025
bibkey: bai2025streaming
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.19206"}
tags: ['Agentic', 'Model Architecture', 'Reinforcement Learning']
---
The latency bottleneck of traditional text-to-speech (TTS) systems fundamentally hinders the potential of streaming large language models (LLMs) in conversational AI. These TTS systems, typically trained and inferenced on complete utterances, introduce unacceptable delays, even with optimized inference speeds, when coupled with streaming LLM outputs. This is particularly problematic for creating responsive conversational agents where low first-token latency is critical. In this paper, we present SpeakStream, a streaming TTS system that generates audio incrementally from streaming text using a decoder-only architecture. SpeakStream is trained using a next-step prediction loss on interleaved text-speech data. During inference, it generates speech incrementally while absorbing streaming input text, making it particularly suitable for cascaded conversational AI agents where an LLM streams text to a TTS system. Our experiments demonstrate that SpeakStream achieves state-of-the-art latency results in terms of first-token latency while maintaining the quality of non-streaming TTS systems.
