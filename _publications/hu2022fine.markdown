---
layout: publication
title: "Fctalker: Fine And Coarse Grained Context Modeling For Expressive Conversational Speech Synthesis"
authors: Hu Yifan, Liu Rui, Gao Guanglai, Li Haizhou
conference: "Arxiv"
year: 2022
bibkey: hu2022fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.15360"}
  - {name: "Code", url: "https://github.com/walker-hyf/FCTalker"}
tags: ['Applications', 'BERT', 'Has Code', 'Model Architecture']
---
Conversational Text-to-Speech (TTS) aims to synthesis an utterance with the right linguistic and affective prosody in a conversational context. The correlation between the current utterance and the dialogue history at the utterance level was used to improve the expressiveness of synthesized speech. However the fine-grained information in the dialogue history at the word level also has an important impact on the prosodic expression of an utterance which has not been well studied in the prior work. Therefore we propose a novel expressive conversational TTS model termed as FCTalker that learn the fine and coarse grained context dependency at the same time during speech generation. Specifically the FCTalker includes fine and coarse grained encoders to exploit the word and utterance-level context dependency. To model the word-level dependencies between an utterance and its dialogue history the fine-grained dialogue encoder is built on top of a dialogue BERT model. The experimental results show that the proposed method outperforms all baselines and generates more expressive speech that is contextually appropriate. We release the source code at https://github.com/walker-hyf/FCTalker."
