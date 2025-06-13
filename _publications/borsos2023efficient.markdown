---
layout: publication
title: 'Soundstorm: Efficient Parallel Audio Generation'
authors: Zalán Borsos, Matt Sharifi, Damien Vincent, Eugene Kharitonov, Neil Zeghidour, Marco Tagliasacchi
conference: "Arxiv"
year: 2023
bibkey: borsos2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.09636"}
tags: ['Model Architecture', 'GPT', 'Pretraining Methods', 'Prompting', 'Attention Mechanism']
---
We present SoundStorm, a model for efficient, non-autoregressive audio
generation. SoundStorm receives as input the semantic tokens of AudioLM, and
relies on bidirectional attention and confidence-based parallel decoding to
generate the tokens of a neural audio codec. Compared to the autoregressive
generation approach of AudioLM, our model produces audio of the same quality
and with higher consistency in voice and acoustic conditions, while being two
orders of magnitude faster. SoundStorm generates 30 seconds of audio in 0.5
seconds on a TPU-v4. We demonstrate the ability of our model to scale audio
generation to longer sequences by synthesizing high-quality, natural dialogue
segments, given a transcript annotated with speaker turns and a short prompt
with the speakers' voices.
