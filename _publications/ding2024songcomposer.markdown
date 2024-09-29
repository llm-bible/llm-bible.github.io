---
layout: publication
title: Songcomposer A Large Language Model For Lyric And Melody Composition In Song Generation
authors: Ding Shuangrui, Liu Zihan, Dong Xiaoyi, Zhang Pan, Qian Rui, He Conghui, Lin Dahua, Wang Jiaqi
conference: "Arxiv"
year: 2024
bibkey: ding2024songcomposer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17645"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
We present SongComposer an innovative LLM designed for song composition. It could understand and generate melodies and lyrics in symbolic song representations by leveraging the capability of LLM. Existing music-related LLM treated the music as quantized audio signals while such implicit encoding leads to inefficient encoding and poor flexibility. In contrast we resort to symbolic song representation the mature and efficient way humans designed for music and enable LLM to explicitly compose songs like humans. In practice we design a novel tuple design to format lyric and three note attributes (pitch duration and rest duration) in the melody which guarantees the correct LLM understanding of musical symbols and realizes precise alignment between lyrics and melody. To impart basic music understanding to LLM we carefully collected SongCompose-PT a large-scale song pretraining dataset that includes lyrics melodies and paired lyrics-melodies in either Chinese or English. After adequate pre-training 10K carefully crafted QA pairs are used to empower the LLM with the instruction-following capability and solve diverse tasks. With extensive experiments SongComposer demonstrates superior performance in lyric-to-melody generation melody-to-lyric generation song continuation and text-to-song creation outperforming advanced LLMs like GPT-4.
