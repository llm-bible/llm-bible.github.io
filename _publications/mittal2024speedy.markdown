---
layout: publication
title: 'SALSA: Speedy ASR-LLM Synchronous Aggregation'
authors: Ashish Mittal, Darshan Prabhu, Sunita Sarawagi, Preethi Jyothi
conference: "Arxiv"
year: 2024
bibkey: mittal2024speedy
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.16542'}
tags: ['Attention Mechanism', 'Training Techniques', 'Model Architecture', 'Merging', 'Reinforcement Learning', 'Tokenization']
---
Harnessing pre-trained LLMs to improve ASR systems, particularly for
low-resource languages, is now an emerging area of research. Existing methods
range from using LLMs for ASR error correction to tightly coupled systems that
replace the ASR decoder with the LLM. These approaches either increase decoding
time or require expensive training of the cross-attention layers. We propose
SALSA, which couples the decoder layers of the ASR to the LLM decoder, while
synchronously advancing both decoders. Such coupling is performed with a simple
projection of the last decoder state, and is thus significantly more training
efficient than earlier approaches. A challenge of our proposed coupling is
handling the mismatch between the tokenizers of the LLM and ASR systems. We
handle this mismatch using cascading tokenization with respect to the LLM and
ASR vocabularies. We evaluate SALSA on 8 low-resource languages in the FLEURS
benchmark, yielding substantial WER reductions of up to 38%.
