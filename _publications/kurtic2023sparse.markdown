---
layout: publication
title: Sparse Fine45;tuning For Inference Acceleration Of Large Language Models
authors: Kurtic Eldar, Kuznedelev Denis, Frantar Elias, Goin Michael, Alistarh Dan
conference: "Arxiv"
year: 2023
bibkey: kurtic2023sparse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.06927"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'GPT', 'Language Modeling', 'Model Architecture', 'Quantization', 'RAG']
---
We consider the problem of accurate sparse fine45;tuning of large language models (LLMs) that is fine45;tuning pretrained LLMs on specialized tasks while inducing sparsity in their weights. On the accuracy side we observe that standard loss45;based fine45;tuning may fail to recover accuracy especially at high sparsities. To address this we perform a detailed study of distillation45;type losses determining an L245;based distillation approach we term SquareHead which enables accurate recovery even at higher sparsities across all model types. On the practical efficiency side we show that sparse LLMs can be executed with speedups by taking advantage of sparsity for both CPU and GPU runtimes. While the standard approach is to leverage sparsity for computational reduction we observe that in the case of memory45;bound LLMs sparsity can also be leveraged for reducing memory bandwidth. We exhibit end45;to45;end results showing speedups due to sparsity while recovering accuracy on T5 (language translation) Whisper (speech translation) and open GPT45;type (MPT for text generation). For MPT text generation we show for the first time that sparse fine45;tuning can reach 7537; sparsity without accuracy drops provide notable end45;to45;end speedups for both CPU and GPU inference and highlight that sparsity is also compatible with quantization approaches. Models and software for reproducing our results are provided in Section 6.
