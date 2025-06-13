---
layout: publication
title: 'Large Language Models Are Strong Audio-visual Speech Recognition Learners'
authors: Umberto Cappellazzo, Minsu Kim, Honglie Chen, Pingchuan Ma, Stavros Petridis, Daniele Falavigna, Alessio Brutti, Maja Pantic
conference: "Arxiv"
year: 2024
bibkey: cappellazzo2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.12319"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Multimodal Models', 'RAG', 'Fine-Tuning', 'Attention Mechanism', 'INTERSPEECH']
---
Multimodal large language models (MLLMs) have recently become a focal point
of research due to their formidable multimodal understanding capabilities. For
example, in the audio and speech domains, an LLM can be equipped with
(automatic) speech recognition (ASR) abilities by just concatenating the audio
tokens, computed with an audio encoder, and the text tokens to achieve
state-of-the-art results. On the contrary, tasks like visual and audio-visual
speech recognition (VSR/AVSR), which also exploit noise-invariant lip movement
information, have received little or no attention. To bridge this gap, we
propose Llama-AVSR, a new MLLM with strong audio-visual speech recognition
capabilities. It leverages pre-trained audio and video encoders to produce
modality-specific tokens which, together with the text tokens, are processed by
a pre-trained LLM (e.g., Llama3.1-8B) to yield the resulting response in an
auto-regressive fashion. Llama-AVSR requires a small number of trainable
parameters as only modality-specific projectors and LoRA modules are trained
whereas the multi-modal encoders and LLM are kept frozen. We evaluate our
proposed approach on LRS3, the largest public AVSR benchmark, and we achieve
new state-of-the-art results for the tasks of ASR and AVSR with a WER of 0.79%
and 0.77%, respectively. To bolster our results, we investigate the key factors
that underpin the effectiveness of Llama-AVSR: the choice of the pre-trained
encoders and LLM, the efficient integration of LoRA modules, and the optimal
performance-efficiency trade-off obtained via modality-aware compression rates.
