---
layout: publication
title: 'Rewriter-evaluator Architecture For Neural Machine Translation'
authors: Yangming Li, Kaisheng Yao
conference: "Arxiv"
year: 2020
bibkey: li2020rewriter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2012.05414"}
tags: ['Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Applications']
---
Encoder-decoder has been widely used in neural machine translation (NMT). A
few methods have been proposed to improve it with multiple passes of decoding.
However, their full potential is limited by a lack of appropriate termination
policies. To address this issue, we present a novel architecture,
Rewriter-Evaluator. It consists of a rewriter and an evaluator. Translating a
source sentence involves multiple passes. At every pass, the rewriter produces
a new translation to improve the past translation and the evaluator estimates
the translation quality to decide whether to terminate the rewriting process.
We also propose prioritized gradient descent (PGD) that facilitates training
the rewriter and the evaluator jointly. Though incurring multiple passes of
decoding, Rewriter-Evaluator with the proposed PGD method can be trained with a
similar time to that of training encoder-decoder models. We apply the proposed
architecture to improve the general NMT models (e.g., Transformer). We conduct
extensive experiments on two translation tasks, Chinese-English and
English-German, and show that the proposed architecture notably improves the
performances of NMT models and significantly outperforms previous baselines.
