---
layout: publication
title: GLM45;130B An Open Bilingual Pre45;trained Model
authors: Aohan Zeng, Xiao Liu, Zhengxiao Du, Zihan Wang, Hanyu Lai, Ming Ding, Zhuoyi Yang, Yifan Xu, Wendi Zheng, Xiao Xia, Weng Lam Tam, Zixuan Ma, Yufei Xue, Jidong Zhai, Wenguang Chen, Peng Zhang, Yuxiao Dong, Jie Tang
conference: "Arxiv"
year: 2022
bibkey: zeng2022glm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2210.02414v2"}
  - {name: "Code", url: "https://github.com/THUDM/GLM&#45;130B/&#125;"}
tags: ['Efficiency And Optimization', 'GPT', 'Has Code', 'Model Architecture', 'Quantization', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
We introduce GLM45;130B a bilingual (English and Chinese) pre45;trained language model with 130 billion parameters. It is an attempt to open45;source a 100B45;scale model at least as good as GPT45;3 (davinci) and unveil how models of such a scale can be successfully pre45;trained. Over the course of this effort we face numerous unexpected technical and engineering challenges particularly on loss spikes and divergence. In this paper we introduce the training process of GLM45;130B including its design choices training strategies for both efficiency and stability and engineering efforts. The resultant GLM45;130B model offers significant outperformance over GPT45;3 175B (davinci) on a wide range of popular English benchmarks while the performance advantage is not observed in OPT45;175B and BLOOM45;176B. It also consistently and significantly outperforms ERNIE TITAN 3.0 260B 45;45; the largest Chinese language model 45;45; across related benchmarks. Finally we leverage a unique scaling property of GLM45;130B to reach INT4 quantization without post training with almost no performance loss making it the first among 100B45;scale models and more importantly allowing its effective inference on 4×RTX 3090 (24G) or 8×RTX 2080 Ti (11G) GPUs the most affordable GPUs required for using 100B45;scale models. The GLM45;130B model weights are publicly accessible and its code training logs related toolkit and lessons learned are open45;sourced at url123;https://github.com/THUDM/GLM&#45;130B/&#125;.
