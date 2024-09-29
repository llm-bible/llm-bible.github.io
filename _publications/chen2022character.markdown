---
layout: publication
title: Character-Centric Story Visualization via Visual Planning and Token Alignment
authors: Chen Hong, Han Rujun, Wu Te-lin, Nakayama Hideki, Peng Nanyun
conference: "Arxiv"
year: 2022
bibkey: chen2022character
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.08465"}
  - {name: "Code", url: "https://github.com/sairin1202/VP-CSV"}
tags: ['Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Transformer']
---
Story visualization advances the traditional text-to-image generation by enabling multiple image generation based on a complete story. This task requires machines to 1) understand long text inputs and 2) produce a globally consistent image sequence that illustrates the contents of the story. A key challenge of consistent story visualization is to preserve characters that are essential in stories. To tackle the challenge we propose to adapt a recent work that augments Vector-Quantized Variational Autoencoders (VQ-VAE) with a text-tovisual-token (transformer) architecture. Specifically we modify the text-to-visual-token module with a two-stage framework 1) character token planning model that predicts the visual tokens for characters only; 2) visual token completion model that generates the remaining visual token sequence which is sent to VQ-VAE for finalizing image generations. To encourage characters to appear in the images we further train the two-stage framework with a character-token alignment objective. Extensive experiments and evaluations demonstrate that the proposed method excels at preserving characters and can produce higher quality image sequences compared with the strong baselines. Codes can be found in https://github.com/sairin1202/VP-CSV
