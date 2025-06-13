---
layout: publication
title: 'BASE TTS: Lessons From Building A Billion-parameter Text-to-speech Model On 100K Hours Of Data'
authors: Mateusz Łajszczak, Guillermo Cámbara, Yang Li, Fatih Beyhan, Arent Van Korlaar, Fan Yang, Arnaud Joly, Álvaro Martín-cortinas, Ammar Abbas, Adam Michalski, Alexis Moinet, Sri Karlapati, Ewa Muszyńska, Haohan Guo, Bartosz Putrycz, Soledad López Gambino, Kayeon Yoo, Elena Sokolova, Thomas Drugman
conference: "Arxiv"
year: 2024
bibkey: łajszczak2024base
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.08093"}
  - {name: "Code", url: "https://amazon-ltts-paper.com/"}
tags: ['Transformer', 'GPT', 'Model Architecture', 'Tokenization', 'Has Code', 'Pretraining Methods']
---
We introduce a text-to-speech (TTS) model called BASE TTS, which stands for
\\(\textbf\{B\}\\)ig \\(\textbf\{A\}\\)daptive \\(\textbf\{S\}\\)treamable TTS with
\\(\textbf\{E\}\\)mergent abilities. BASE TTS is the largest TTS model to-date,
trained on 100K hours of public domain speech data, achieving a new
state-of-the-art in speech naturalness. It deploys a 1-billion-parameter
autoregressive Transformer that converts raw texts into discrete codes
("speechcodes") followed by a convolution-based decoder which converts these
speechcodes into waveforms in an incremental, streamable manner. Further, our
speechcodes are built using a novel speech tokenization technique that features
speaker ID disentanglement and compression with byte-pair encoding. Echoing the
widely-reported "emergent abilities" of large language models when trained on
increasing volume of data, we show that BASE TTS variants built with 10K+ hours
and 500M+ parameters begin to demonstrate natural prosody on textually complex
sentences. We design and share a specialized dataset to measure these emergent
abilities for text-to-speech. We showcase state-of-the-art naturalness of BASE
TTS by evaluating against baselines that include publicly available large-scale
text-to-speech systems: YourTTS, Bark and TortoiseTTS. Audio samples generated
by the model can be heard at https://amazon-ltts-paper.com/.
