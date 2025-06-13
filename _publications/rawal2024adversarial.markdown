---
layout: publication
title: 'Aigen: An Adversarial Approach For Instruction Generation In VLN'
authors: Niyati Rawal, Roberto Bigazzi, Lorenzo Baraldi, Rita Cucchiara
conference: "Arxiv"
year: 2024
bibkey: rawal2024adversarial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10054"}
tags: ['Transformer', 'Agentic', 'GPT', 'Model Architecture', 'Security', 'Training Techniques', 'Pretraining Methods', 'BERT']
---
In the last few years, the research interest in Vision-and-Language
Navigation (VLN) has grown significantly. VLN is a challenging task that
involves an agent following human instructions and navigating in a previously
unknown environment to reach a specified goal. Recent work in literature
focuses on different ways to augment the available datasets of instructions for
improving navigation performance by exploiting synthetic training data. In this
work, we propose AIGeN, a novel architecture inspired by Generative Adversarial
Networks (GANs) that produces meaningful and well-formed synthetic instructions
to improve navigation agents' performance. The model is composed of a
Transformer decoder (GPT-2) and a Transformer encoder (BERT). During the
training phase, the decoder generates sentences for a sequence of images
describing the agent's path to a particular point while the encoder
discriminates between real and fake instructions. Experimentally, we evaluate
the quality of the generated instructions and perform extensive ablation
studies. Additionally, we generate synthetic instructions for 217K trajectories
using AIGeN on Habitat-Matterport 3D Dataset (HM3D) and show an improvement in
the performance of an off-the-shelf VLN method. The validation analysis of our
proposal is conducted on REVERIE and R2R and highlights the promising aspects
of our proposal, achieving state-of-the-art performance.
