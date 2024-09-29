---
layout: publication
title: Compression Of Generative Pre45;trained Language Models Via Quantization
authors: Tao Chaofan, Hou Lu, Zhang Wei, Shang Lifeng, Jiang Xin, Liu Qun, Luo Ping, Wong Ngai
conference: "Arxiv"
year: 2022
bibkey: tao2022compression
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.10705"}
tags: ['BERT', 'Distillation', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Quantization', 'Reinforcement Learning']
---
The increasing size of generative Pre45;trained Language Models (PLMs) has greatly increased the demand for model compression. Despite various methods to compress BERT or its variants there are few attempts to compress generative PLMs and the underlying difficulty remains unclear. In this paper we compress generative PLMs by quantization. We find that previous quantization methods fail on generative tasks due to the textit123;homogeneous word embeddings125; caused by reduced capacity and textit123;varied distribution of weights125;. Correspondingly we propose a token45;level contrastive distillation to learn distinguishable word embeddings and a module45;wise dynamic scaling to make quantizers adaptive to different modules. Empirical results on various tasks show that our proposed method outperforms the state45;of45;the45;art compression methods on generative PLMs by a clear margin. With comparable performance with the full45;precision models we achieve 14.4x and 13.4x compression rates on GPT45;2 and BART respectively.
