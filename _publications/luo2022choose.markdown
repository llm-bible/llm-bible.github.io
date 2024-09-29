---
layout: publication
title: Choose Your QA Model Wisely A Systematic Study Of Generative And Extractive Readers For Question Answering
authors: Luo Man, Hashimoto Kazuma, Yavuz Semih, Liu Zhiwei, Baral Chitta, Zhou Yingbo
conference: "Arxiv"
year: 2022
bibkey: luo2022choose
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.07522"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
While both extractive and generative readers have been successfully applied to the Question Answering (QA) task little attention has been paid toward the systematic comparison of them. Characterizing the strengths and weaknesses of the two readers is crucial not only for making a more informed reader selection in practice but also for developing a deeper understanding to foster further research on improving readers in a principled manner. Motivated by this goal we make the first attempt to systematically study the comparison of extractive and generative readers for question answering. To be aligned with the state45;of45;the45;art we explore nine transformer45;based large pre45;trained language models (PrLMs) as backbone architectures. Furthermore we organize our findings under two main categories (1) keeping the architecture invariant and (2) varying the underlying PrLMs. Among several interesting findings it is important to highlight that (1) the generative readers perform better in long context QA (2) the extractive readers perform better in short context while also showing better out45;of45;domain generalization and (3) the encoder of encoder45;decoder PrLMs (e.g. T5) turns out to be a strong extractive reader and outperforms the standard choice of encoder45;only PrLMs (e.g. RoBERTa). We also study the effect of multi45;task learning on the two types of readers varying the underlying PrLMs and perform qualitative and quantitative diagnosis to provide further insights into future directions in modeling better readers.
