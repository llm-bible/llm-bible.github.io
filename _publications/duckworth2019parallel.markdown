---
layout: publication
title: Parallel Scheduled Sampling
authors: Duckworth Daniel, Neelakantan Arvind, Goodrich Ben, Kaiser Lukasz, Bengio Samy
conference: "Arxiv"
year: 2019
bibkey: duckworth2019parallel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1906.04331"}
tags: ['Applications', 'Training Techniques']
---
Auto45;regressive models are widely used in sequence generation problems. The output sequence is typically generated in a predetermined order one discrete unit (pixel or word or character) at a time. The models are trained by teacher45;forcing where ground45;truth history is fed to the model as input which at test time is replaced by the model prediction. Scheduled Sampling aims to mitigate this discrepancy between train and test time by randomly replacing some discrete units in the history with the models prediction. While teacher45;forced training works well with ML accelerators as the computation can be parallelized across time Scheduled Sampling involves undesirable sequential processing. In this paper we introduce a simple technique to parallelize Scheduled Sampling across time. Experimentally we find the proposed technique leads to equivalent or better performance on image generation summarization dialog generation and translation compared to teacher45;forced training. In dialog response generation task Parallel Scheduled Sampling achieves 1.6 BLEU score (11.537;) improvement over teacher45;forcing while in image generation it achieves 2037; and 13.837; improvement in Frechet Inception Distance (FID) and Inception Score (IS) respectively. Further we discuss the effects of different hyper45;parameters associated with Scheduled Sampling on the model performance.
