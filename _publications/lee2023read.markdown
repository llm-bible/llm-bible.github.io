---
layout: publication
title: Read45;only Prompt Optimization For Vision45;language Few45;shot Learning
authors: Lee Dongjun, Song Seokwon, Suh Jihee, Choi Joonmyung, Lee Sanghyeok, Kim Hyunwoo J.
conference: "Arxiv"
year: 2023
bibkey: lee2023read
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.14960"}
  - {name: "Code", url: "https://github.com/mlvlab/RPO"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Security']
---
In recent years prompt tuning has proven effective in adapting pre45;trained vision45;language models to downstream tasks. These methods aim to adapt the pre45;trained models by introducing learnable prompts while keeping pre45;trained weights frozen. However learnable prompts can affect the internal representation within the self45;attention module which may negatively impact performance variance and generalization especially in data45;deficient settings. To address these issues we propose a novel approach Read45;only Prompt Optimization (RPO). RPO leverages masked attention to prevent the internal representation shift in the pre45;trained model. Further to facilitate the optimization of RPO the read45;only prompts are initialized based on special tokens of the pre45;trained model. Our extensive experiments demonstrate that RPO outperforms CLIP and CoCoOp in base45;to45;new generalization and domain generalization while displaying better robustness. Also the proposed method achieves better generalization on extremely data45;deficient settings while improving parameter efficiency and computational overhead. Code is available at https://github.com/mlvlab/RPO.
