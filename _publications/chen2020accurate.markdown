---
layout: publication
title: Accurate Word Alignment Induction from Neural Machine Translation
authors: Chen Yun, Liu Yang, Chen Guanhua, Jiang Xin, Liu Qun
conference: "Arxiv"
year: 2020
bibkey: chen2020accurate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.14837"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Despite its original goal to jointly learn to align and translate prior researches suggest that Transformer captures poor word alignments through its attention mechanism. In this paper we show that attention weights DO capture accurate word alignments and propose two novel word alignment induction methods Shift-Att and Shift-AET. The main idea is to induce alignments at the step when the to-be-aligned target token is the decoder input rather than the decoder output as in previous work. Shift-Att is an interpretation method that induces alignments from the attention weights of Transformer and does not require parameter update or architecture change. Shift-AET extracts alignments from an additional alignment module which is tightly integrated into Transformer and trained in isolation with supervision from symmetrized Shift-Att alignments. Experiments on three publicly available datasets demonstrate that both methods perform better than their corresponding neural baselines and Shift-AET significantly outperforms GIZA++ by 1.4-4.8 AER points.
