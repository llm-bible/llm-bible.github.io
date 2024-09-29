---
layout: publication
title: Epi-curriculum: Episodic Curriculum Learning For Low-resource Domain Adaptation In Neural Machine Translation
authors: Chen Keyu, Zhuang Di, Li Mingchen, Chang J. Morris
conference: "Arxiv"
year: 2023
bibkey: chen2023epi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.02640"}
tags: ['Applications', 'Fine Tuning', 'Security', 'Tools', 'Training Techniques']
---
Neural Machine Translation (NMT) models have become successful but their performance remains poor when translating on new domains with a limited number of data. In this paper we present a novel approach Epi-Curriculum to address low-resource domain adaptation (DA) which contains a new episodic training framework along with denoised curriculum learning. Our episodic training framework enhances the models robustness to domain shift by episodically exposing the encoder/decoder to an inexperienced decoder/encoder. The denoised curriculum learning filters the noised data and further improves the models adaptability by gradually guiding the learning process from easy to more difficult tasks. Experiments on English-German and English-Romanian translation show that (i) Epi-Curriculum improves both models robustness and adaptability in seen and unseen domains; (ii) Our episodic training framework enhances the encoder and decoders robustness to domain shift.
