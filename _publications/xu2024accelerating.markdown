---
layout: publication
title: Accelerating Large Language Model Training With Hybrid Gpu45;based Compression
authors: Xu Lang, Anthony Quentin, Zhou Qinghua, Alnaasan Nawras, Gulhane Radha R., Shafi Aamir, Subramoni Hari, Panda Dhabaleswar K.
conference: "Arxiv"
year: 2024
bibkey: xu2024accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.02423"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'RAG', 'Training Techniques']
---
Data Parallelism (DP) Tensor Parallelism (TP) and Pipeline Parallelism (PP) are the three strategies widely adopted to enable fast and efficient Large Language Model (LLM) training. However these approaches rely on data45;intensive communication routines to collect aggregate and re45;distribute gradients activations and other important model information which pose significant overhead. Co45;designed with GPU45;based compression libraries MPI libraries have been proven to reduce message size significantly and leverage interconnect bandwidth thus increasing training efficiency while maintaining acceptable accuracy. In this work we investigate the efficacy of compression45;assisted MPI collectives under the context of distributed LLM training using 3D parallelism and ZeRO optimizations. We scaled up to 192 V100 GPUs on the Lassen supercomputer. First we enabled a naive compression scheme across all collectives and observed a 22.537; increase in TFLOPS per GPU and a 23.637; increase in samples per second for GPT45;NeoX45;20B training. Nonetheless such a strategy ignores the sparsity discrepancy among messages communicated in each parallelism degree thus introducing more errors and causing degradation in training loss. Therefore we incorporated hybrid compression settings toward each parallel dimension and adjusted the compression intensity accordingly. Given their low45;rank structure (arXiv2301.02654) we apply aggressive compression on gradients when performing DP All45;reduce. We adopt milder compression to preserve precision while communicating activations optimizer states and model parameters in TP and PP. Using the adjusted hybrid compression scheme we demonstrate a 17.337; increase in TFLOPS per GPU and a 12.737; increase in samples per second while reaching baseline loss convergence.
