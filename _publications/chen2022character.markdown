---
layout: publication
title: Character45;centric Story Visualization Via Visual Planning And Token Alignment
authors: Chen Hong, Han Rujun, Wu Te-lin, Nakayama Hideki, Peng Nanyun
conference: "Arxiv"
year: 2022
bibkey: chen2022character
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.08465"}
  - {name: "Code", url: "https://github.com/sairin1202/VP&#45;CSV"}
tags: ['Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Transformer']
---
Story visualization advances the traditional text45;to45;image generation by enabling multiple image generation based on a complete story. This task requires machines to 1) understand long text inputs and 2) produce a globally consistent image sequence that illustrates the contents of the story. A key challenge of consistent story visualization is to preserve characters that are essential in stories. To tackle the challenge we propose to adapt a recent work that augments Vector45;Quantized Variational Autoencoders (VQ45;VAE) with a text45;tovisual45;token (transformer) architecture. Specifically we modify the text45;to45;visual45;token module with a two45;stage framework 1) character token planning model that predicts the visual tokens for characters only; 2) visual token completion model that generates the remaining visual token sequence which is sent to VQ45;VAE for finalizing image generations. To encourage characters to appear in the images we further train the two45;stage framework with a character45;token alignment objective. Extensive experiments and evaluations demonstrate that the proposed method excels at preserving characters and can produce higher quality image sequences compared with the strong baselines. Codes can be found in https://github.com/sairin1202/VP&#45;CSV
