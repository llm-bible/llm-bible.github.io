---
layout: publication
title: 'Avhbench: A Cross-modal Hallucination Benchmark For Audio-visual Large Language Models'
authors: Kim Sung-bin, Oh Hyun-bin, Jungmok Lee, Arda Senocak, Joon Son Chung, Tae-hyun Oh
conference: "Arxiv"
year: 2024
bibkey: sungbin2024cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.18325"}
  - {name: "Code", url: "https://github.com/kaist-ami/AVHBench"}
tags: ['Security', 'Training Techniques', 'Multimodal Models', 'Reinforcement Learning', 'Has Code']
---
Following the success of Large Language Models (LLMs), expanding their
boundaries to new modalities represents a significant paradigm shift in
multimodal understanding. Human perception is inherently multimodal, relying
not only on text but also on auditory and visual cues for a complete
understanding of the world. In recognition of this fact, audio-visual LLMs have
recently emerged. Despite promising developments, the lack of dedicated
benchmarks poses challenges for understanding and evaluating models. In this
work, we show that audio-visual LLMs struggle to discern subtle relationships
between audio and visual signals, leading to hallucinations and highlighting
the need for reliable benchmarks. To address this, we introduce AVHBench, the
first comprehensive benchmark specifically designed to evaluate the perception
and comprehension capabilities of audio-visual LLMs. Our benchmark includes
tests for assessing hallucinations, as well as the cross-modal matching and
reasoning abilities of these models. Our results reveal that most existing
audio-visual LLMs struggle with hallucinations caused by cross-interactions
between modalities, due to their limited capacity to perceive complex
multimodal signals and their relationships. Additionally, we demonstrate that
simple training with our AVHBench improves robustness of audio-visual LLMs
against hallucinations. Dataset: https://github.com/kaist-ami/AVHBench
