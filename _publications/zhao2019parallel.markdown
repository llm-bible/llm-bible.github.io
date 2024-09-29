---
layout: publication
title: MUSE Parallel Multi45;scale Attention For Sequence To Sequence Learning
authors: Zhao Guangxiang, Sun Xu, Xu Jingjing, Zhang Zhiyuan, Luo Liangchen
conference: "Arxiv"
year: 2019
bibkey: zhao2019parallel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1911.09483"}
  - {name: "Code", url: "https://github.com/lancopku/MUSE"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
In sequence to sequence learning the self45;attention mechanism proves to be highly effective and achieves significant improvements in many tasks. However the self45;attention mechanism is not without its own flaws. Although self45;attention can model extremely long dependencies the attention in deep layers tends to overconcentrate on a single token leading to insufficient use of local information and difficultly in representing long sequences. In this work we explore parallel multi45;scale representation learning on sequence data striving to capture both long45;range and short45;range language structures. To this end we propose the Parallel MUlti45;Scale attEntion (MUSE) and MUSE45;simple. MUSE45;simple contains the basic idea of parallel multi45;scale sequence representation learning and it encodes the sequence in parallel in terms of different scales with the help from self45;attention and pointwise transformation. MUSE builds on MUSE45;simple and explores combining convolution and self45;attention for learning sequence representations from more different scales. We focus on machine translation and the proposed approach achieves substantial performance improvements over Transformer especially on long sequences. More importantly we find that although conceptually simple its success in practice requires intricate considerations and the multi45;scale attention must build on unified semantic space. Under common setting the proposed model achieves substantial performance and outperforms all previous models on three main machine translation tasks. In addition MUSE has potential for accelerating inference due to its parallelism. Code will be available at https://github.com/lancopku/MUSE
