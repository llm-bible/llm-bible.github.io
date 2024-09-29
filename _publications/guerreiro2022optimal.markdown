---
layout: publication
title: Optimal Transport for Unsupervised Hallucination Detection in Neural Machine Translation
authors: Guerreiro Nuno M., Colombo Pierre, Piantanida Pablo, Martins André F. T.
conference: "Arxiv"
year: 2022
bibkey: guerreiro2022optimal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.09631"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Reinforcement Learning']
---
Neural machine translation (NMT) has become the de-facto standard in real-world machine translation applications. However NMT models can unpredictably produce severely pathological translations known as hallucinations that seriously undermine user trust. It becomes thus crucial to implement effective preventive strategies to guarantee their proper functioning. In this paper we address the problem of hallucination detection in NMT by following a simple intuition as hallucinations are detached from the source content they exhibit encoder-decoder attention patterns that are statistically different from those of good quality translations. We frame this problem with an optimal transport formulation and propose a fully unsupervised plug-in detector that can be used with any attention-based NMT model. Experimental results show that our detector not only outperforms all previous model-based detectors but is also competitive with detectors that employ large models trained on millions of samples.
