---
layout: publication
title: Voicebox Text45;guided Multilingual Universal Speech Generation At Scale
authors: Le Matthew, Vyas Apoorv, Shi Bowen, Karrer Brian, Sari Leda, Moritz Rashel, Williamson Mary, Manohar Vimal, Adi Yossi, Mahadeokar Jay, Hsu Wei-ning
conference: "Arxiv"
year: 2023
bibkey: le2023text
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.15687"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning']
---
Large45;scale generative models such as GPT and DALL45;E have revolutionized the research community. These models not only generate high fidelity outputs but are also generalists which can solve tasks not explicitly taught. In contrast speech generative models are still primitive in terms of scale and task generalization. In this paper we present Voicebox the most versatile text45;guided generative model for speech at scale. Voicebox is a non45;autoregressive flow45;matching model trained to infill speech given audio context and text trained on over 50K hours of speech that are not filtered or enhanced. Similar to GPT Voicebox can perform many different tasks through in45;context learning but is more flexible as it can also condition on future context. Voicebox can be used for mono or cross45;lingual zero45;shot text45;to45;speech synthesis noise removal content editing style conversion and diverse sample generation. In particular Voicebox outperforms the state45;of45;the45;art zero45;shot TTS model VALL45;E on both intelligibility (5.937; vs 1.937; word error rates) and audio similarity (0.580 vs 0.681) while being up to 20 times faster. Audio samples can be found in url123;https://voicebox.metademolab.com&#125;.
