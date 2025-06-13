---
layout: publication
title: 'VX2TEXT: End-to-end Learning Of Video-based Text Generation From Multimodal Inputs'
authors: Xudong Lin, Gedas Bertasius, Jue Wang, Shih-fu Chang, Devi Parikh, Lorenzo Torresani
conference: "Arxiv"
year: 2021
bibkey: lin2021end
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2101.12059"}
tags: ['Transformer', 'Tools', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Language Modeling', 'Merging', 'Training Techniques', 'Tokenization', 'Pretraining Methods', 'Multimodal Models']
---
We present \textsc\{Vx2Text\}, a framework for text generation from multimodal
inputs consisting of video plus text, speech, or audio. In order to leverage
transformer networks, which have been shown to be effective at modeling
language, each modality is first converted into a set of language embeddings by
a learnable tokenizer. This allows our approach to perform multimodal fusion in
the language space, thus eliminating the need for ad-hoc cross-modal fusion
modules. To address the non-differentiability of tokenization on continuous
inputs (e.g., video or audio), we utilize a relaxation scheme that enables
end-to-end training. Furthermore, unlike prior encoder-only models, our network
includes an autoregressive decoder to generate open-ended text from the
multimodal embeddings fused by the language encoder. This renders our approach
fully generative and makes it directly applicable to different "video+\\(x\\) to
text" problems without the need to design specialized network heads for each
task. The proposed framework is not only conceptually simple but also
remarkably effective: experiments demonstrate that our approach based on a
single architecture outperforms the state-of-the-art on three video-based
text-generation tasks -- captioning, question answering and audio-visual
scene-aware dialog.
