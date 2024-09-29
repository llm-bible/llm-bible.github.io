---
layout: publication
title: VX2TEXT End45;to45;end Learning Of Video45;based Text Generation From Multimodal Inputs
authors: Lin Xudong, Bertasius Gedas, Wang Jue, Chang Shih-fu, Parikh Devi, Torresani Lorenzo
conference: "Arxiv"
year: 2021
bibkey: lin2021end
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2101.12059"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Tokenization', 'Tools', 'Training Techniques', 'Transformer']
---
We present textsc123;Vx2Text125; a framework for text generation from multimodal inputs consisting of video plus text speech or audio. In order to leverage transformer networks which have been shown to be effective at modeling language each modality is first converted into a set of language embeddings by a learnable tokenizer. This allows our approach to perform multimodal fusion in the language space thus eliminating the need for ad45;hoc cross45;modal fusion modules. To address the non45;differentiability of tokenization on continuous inputs (e.g. video or audio) we utilize a relaxation scheme that enables end45;to45;end training. Furthermore unlike prior encoder45;only models our network includes an autoregressive decoder to generate open45;ended text from the multimodal embeddings fused by the language encoder. This renders our approach fully generative and makes it directly applicable to different video+x to text problems without the need to design specialized network heads for each task. The proposed framework is not only conceptually simple but also remarkably effective experiments demonstrate that our approach based on a single architecture outperforms the state45;of45;the45;art on three video45;based text45;generation tasks 45;45; captioning question answering and audio45;visual scene45;aware dialog.
