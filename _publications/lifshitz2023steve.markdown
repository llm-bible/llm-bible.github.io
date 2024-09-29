---
layout: publication
title: STEVE45;1 A Generative Model For Text45;to45;behavior In Minecraft
authors: Lifshitz Shalev, Paster Keiran, Chan Harris, Ba Jimmy, Mcilraith Sheila
conference: "Arxiv"
year: 2023
bibkey: lifshitz2023steve
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.00937"}
tags: ['Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Constructing AI models that respond to text instructions is challenging especially for sequential decision45;making tasks. This work introduces a methodology inspired by unCLIP for instruction45;tuning generative models of behavior without relying on a large dataset of instruction45;labeled trajectories. Using this methodology we create an instruction45;tuned Video Pretraining (VPT) model called STEVE45;1 which can follow short45;horizon open45;ended text and visual instructions in Minecraft. STEVE45;1 is trained in two steps adapting the pretrained VPT model to follow commands in MineCLIPs latent space then training a prior to predict latent codes from text. This allows us to finetune VPT through self45;supervised behavioral cloning and hindsight relabeling reducing the need for costly human text annotations and all for only 60 of compute. By leveraging pretrained models like VPT and MineCLIP and employing best practices from text45;conditioned image generation STEVE45;1 sets a new bar for open45;ended instruction45;following in Minecraft with low45;level controls (mouse and keyboard) and raw pixel inputs far outperforming previous baselines and robustly completing 12 of 13 tasks in our early45;game evaluation suite. We provide experimental evidence highlighting key factors for downstream performance including pretraining classifier45;free guidance and data scaling. All resources including our model weights training scripts and evaluation tools are made available for further research.
