---
layout: publication
title: 'Applying Llms For Rescoring N-best ASR Hypotheses Of Casual Conversations: Effects Of Domain Adaptation And Context Carry-over'
authors: Atsunori Ogawa, Naoyuki Kamo, Kohei Matsuura, Takanori Ashihara, Takafumi Moriya, Takatomo Kano, Naohiro Tawara, Marc Delcroix
conference: "Arxiv"
year: 2024
bibkey: ogawa2024applying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.18972'}
tags: ['Transformer', 'INTERSPEECH', 'Model Architecture', 'Fine-Tuning', 'Pretraining Methods']
---
Large language models (LLMs) have been successfully applied for rescoring
automatic speech recognition (ASR) hypotheses. However, their ability to
rescore ASR hypotheses of casual conversations has not been sufficiently
explored. In this study, we reveal it by performing N-best ASR hypotheses
rescoring using Llama2 on the CHiME-7 distant ASR (DASR) task. Llama2 is one of
the most representative LLMs, and the CHiME-7 DASR task provides datasets of
casual conversations between multiple participants. We investigate the effects
of domain adaptation of the LLM and context carry-over when performing N-best
rescoring. Experimental results show that, even without domain adaptation,
Llama2 outperforms a standard-size domain-adapted Transformer-LM, especially
when using a long context. Domain adaptation shortens the context length needed
with Llama2 to achieve its best performance, i.e., it reduces the computational
cost of Llama2.
