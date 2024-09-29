---
layout: publication
title: 'Harnessing The Zero-shot Power Of Instruction-tuned Large Language Model In End-to-end Speech Recognition'
authors: Higuchi Yosuke, Ogawa Tetsuji, Kobayashi Tetsunori
conference: "Arxiv"
year: 2023
bibkey: higuchi2023harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.10524"}
tags: ['Applications', 'Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Prompting']
---
We present a novel integration of an instruction-tuned large language model (LLM) and end-to-end automatic speech recognition (ASR). Modern LLMs can perform a wide range of linguistic tasks within zero-shot learning when provided with a precise instruction or a prompt to guide the text generation process towards the desired task. We explore using this zero-shot capability of LLMs to extract linguistic information that can contribute to improving ASR performance. Specifically we direct an LLM to correct grammatical errors in an ASR hypothesis and harness the embedded linguistic knowledge to conduct end-to-end ASR. The proposed model is built on the hybrid connectionist temporal classification (CTC) and attention architecture where an instruction-tuned LLM (i.e. Llama2) is employed as a front-end of the decoder. An ASR hypothesis subject to correction is obtained from the encoder via CTC decoding which is then fed into the LLM along with an instruction. The decoder subsequently takes as input the LLM embeddings to perform sequence generation incorporating acoustic information from the encoder output. Experimental results and analyses demonstrate that the proposed integration yields promising performance improvements and our approach largely benefits from LLM-based rescoring.
