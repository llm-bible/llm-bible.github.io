---
layout: publication
title: 'Harnessing The Zero-shot Power Of Instruction-tuned Large Language Model In End-to-end Speech Recognition'
authors: Yosuke Higuchi, Tetsuji Ogawa, Tetsunori Kobayashi
conference: "Arxiv"
year: 2023
bibkey: higuchi2023harnessing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.10524'}
tags: ['Attention Mechanism', 'Language Modeling', 'INTERSPEECH', 'Model Architecture', 'Applications', 'Prompting']
---
We propose to utilize an instruction-tuned large language model (LLM) for
guiding the text generation process in automatic speech recognition (ASR).
Modern large language models (LLMs) are adept at performing various text
generation tasks through zero-shot learning, prompted with instructions
designed for specific objectives. This paper explores the potential of LLMs to
derive linguistic information that can facilitate text generation in end-to-end
ASR models. Specifically, we instruct an LLM to correct grammatical errors in
an ASR hypothesis and use the LLM-derived representations to refine the output
further. The proposed model is built on the joint CTC and attention
architecture, with the LLM serving as a front-end feature extractor for the
decoder. The ASR hypothesis, subject to correction, is obtained from the
encoder via CTC decoding and fed into the LLM along with a specific
instruction. The decoder subsequently takes as input the LLM output to perform
token predictions, combining acoustic information from the encoder and the
powerful linguistic information provided by the LLM. Experimental results show
that the proposed LLM-guided model achieves a relative gain of approximately
13% in word error rates across major benchmarks.
