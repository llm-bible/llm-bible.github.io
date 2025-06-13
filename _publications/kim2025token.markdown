---
layout: publication
title: 'Tokensynth: A Token-based Neural Synthesizer For Instrument Cloning And Text-to-instrument'
authors: Kyungsu Kim, Junghyun Koo, Sungho Lee, Haesun Joung, Kyogu Lee
conference: "Arxiv"
year: 2025
bibkey: kim2025token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08939"}
  - {name: "Code", url: "https://github.com/KyungsuKim42/tokensynth"}
tags: ['Fine-Tuning', 'Transformer', 'RAG', 'Model Architecture', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Recent advancements in neural audio codecs have enabled the use of tokenized
audio representations in various audio generation tasks, such as
text-to-speech, text-to-audio, and text-to-music generation. Leveraging this
approach, we propose TokenSynth, a novel neural synthesizer that utilizes a
decoder-only transformer to generate desired audio tokens from MIDI tokens and
CLAP (Contrastive Language-Audio Pretraining) embedding, which has
timbre-related information. Our model is capable of performing instrument
cloning, text-to-instrument synthesis, and text-guided timbre manipulation
without any fine-tuning. This flexibility enables diverse sound design and
intuitive timbre control. We evaluated the quality of the synthesized audio,
the timbral similarity between synthesized and target audio/text, and synthesis
accuracy (i.e., how accurately it follows the input MIDI) using objective
measures. TokenSynth demonstrates the potential of leveraging advanced neural
audio codecs and transformers to create powerful and versatile neural
synthesizers. The source code, model weights, and audio demos are available at:
https://github.com/KyungsuKim42/tokensynth
