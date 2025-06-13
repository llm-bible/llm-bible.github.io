---
layout: publication
title: 'Seamlessm4t: Massively Multilingual & Multimodal Machine Translation'
authors: Seamless Communication, Loïc Barrault, Yu-an Chung, Mariano Cora Meglioli, David Dale, Ning Dong, Paul-ambroise Duquenne, Hady Elsahar, Hongyu Gong, Kevin Heffernan, John Hoffman, Christopher Klaiber, Pengwei Li, Daniel Licht, Jean Maillard, Alice Rakotoarison, Kaushik Ram Sadagopan, Guillaume Wenzek, Ethan Ye, Bapi Akula, Peng-jen Chen, Naji El Hachem, Brian Ellis, Gabriel Mejia Gonzalez, Justin Haaheim, Prangthip Hansanti, Russ Howes, Bernie Huang, Min-jae Hwang, Hirofumi Inaguma, Somya Jain, Elahe Kalbassi, Amanda Kallet, Ilia Kulikov, Janice Lam, Daniel Li, Xutai Ma, Ruslan Mavlyutov, Benjamin Peloquin, Mohamed Ramadan, Abinesh Ramakrishnan, Anna Sun, Kevin Tran, Tuan Tran, Igor Tufanov, Vish Vogeti, Carleigh Wood, Yilin Yang, Bokai Yu, Pierre Andrews, Can Balioglu, Marta R. Costa-jussà, Onur Celebi, Maha Elbayad, Cynthia Gao, Francisco Guzmán, Justine Kao, Ann Lee, Alexandre Mourachko, Juan Pino, Sravya Popuri, Christophe Ropers, Safiyyah Saleem, Holger Schwenk, Paden Tomasello, Changhan Wang, Jeff Wang, Skyler Wang
conference: "Arxiv"
year: 2023
bibkey: communication2023massively
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.11596"}
  - {name: "Code", url: "https://github.com/facebookresearch/seamless_communication"}
tags: ['Responsible AI', 'Security', 'Model Architecture', 'Training Techniques', 'Multimodal Models', 'Reinforcement Learning', 'RAG', 'Ethics and Bias', 'BERT', 'Has Code', 'Applications', 'INTERSPEECH']
---
What does it take to create the Babel Fish, a tool that can help individuals
translate speech between any two languages? While recent breakthroughs in
text-based models have pushed machine translation coverage beyond 200
languages, unified speech-to-speech translation models have yet to achieve
similar strides. More specifically, conventional speech-to-speech translation
systems rely on cascaded systems that perform translation progressively,
putting high-performing unified systems out of reach. To address these gaps, we
introduce SeamlessM4T, a single model that supports speech-to-speech
translation, speech-to-text translation, text-to-speech translation,
text-to-text translation, and automatic speech recognition for up to 100
languages. To build this, we used 1 million hours of open speech audio data to
learn self-supervised speech representations with w2v-BERT 2.0. Subsequently,
we created a multimodal corpus of automatically aligned speech translations.
Filtered and combined with human-labeled and pseudo-labeled data, we developed
the first multilingual system capable of translating from and into English for
both speech and text. On FLEURS, SeamlessM4T sets a new standard for
translations into multiple target languages, achieving an improvement of 20%
BLEU over the previous SOTA in direct speech-to-text translation. Compared to
strong cascaded models, SeamlessM4T improves the quality of into-English
translation by 1.3 BLEU points in speech-to-text and by 2.6 ASR-BLEU points in
speech-to-speech. Tested for robustness, our system performs better against
background noises and speaker variations in speech-to-text tasks compared to
the current SOTA model. Critically, we evaluated SeamlessM4T on gender bias and
added toxicity to assess translation safety. Finally, all contributions in this
work are open-sourced and accessible at
https://github.com/facebookresearch/seamless_communication
