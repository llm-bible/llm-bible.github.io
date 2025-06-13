---
layout: publication
title: 'Audiochatllama: Towards General-purpose Speech Abilities For Llms'
authors: Yassir Fathullah, Chunyang Wu, Egor Lakomkin, Ke Li, Junteng Jia, Yuan Shangguan, Jay Mahadeokar, Ozlem Kalinli, Christian Fuegen, Mike Seltzer
conference: "Arxiv"
year: 2023
bibkey: fathullah2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.06753"}
tags: ['Multimodal Models', 'Prompting', 'Applications']
---
In this work, we extend the instruction-tuned Llama-2 model with end-to-end
general-purpose speech processing and reasoning abilities while maintaining the
wide range of original LLM capabilities, without using any carefully curated
paired data. The resulting end-to-end model, named AudioChatLlama, can utilize
audio prompts as a replacement for text and sustain a conversation. Such a
model also has extended cross-modal capabilities such as being able to perform
spoken question answering (QA), speech translation, and audio summarization
amongst many other closed and open-domain tasks. This is unlike prior
approaches in speech, in which LLMs are extended to handle audio for a limited
number of pre-designated tasks. On both synthesized and recorded speech QA test
sets, evaluations show that our end-to-end approach is on par with or
outperforms cascaded systems (speech recognizer + LLM) in terms of modeling the
response to a prompt. Furthermore, unlike cascades, our approach can
interchange text and audio modalities and intrinsically utilize prior context
in a conversation to provide better results.
