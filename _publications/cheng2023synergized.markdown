---
layout: publication
title: SCALE Synergized Collaboration Of Asymmetric Language Translation Engines
authors: Cheng Xin, Wang Xun, Ge Tao, Chen Si-qing, Wei Furu, Zhao Dongyan, Yan Rui
conference: "Arxiv"
year: 2023
bibkey: cheng2023synergized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.17061"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'RAG', 'Security', 'Tools']
---
In this paper we introduce SCALE a collaborative framework that connects compact Specialized Translation Models (STMs) and general45;purpose Large Language Models (LLMs) as one unified translation engine. By introducing translation from STM into the triplet in45;context demonstrations SCALE unlocks refinement and pivoting ability of LLM thus mitigating language bias of LLM and parallel data bias of STM enhancing LLM speciality without sacrificing generality and facilitating continual learning without expensive LLM fine45;tuning. Our comprehensive experiments show that SCALE significantly outperforms both few45;shot LLMs (GPT45;4) and specialized models (NLLB) in challenging low45;resource settings. Moreover in Xhosa to English translation SCALE experiences consistent improvement by a 4 BLEURT score without tuning LLM and surpasses few45;shot GPT45;4 by 2.5 COMET score and 3.8 BLEURT score when equipped with a compact model consisting of merely 600M parameters. SCALE could also effectively exploit the existing language bias of LLMs by using an English45;centric STM as a pivot for translation between any language pairs outperforming few45;shot GPT45;4 by an average of 6 COMET points across eight translation directions. Furthermore we provide an in45;depth analysis of SCALEs robustness translation characteristics and latency costs providing solid foundation for future studies exploring the potential synergy between LLMs and more specialized task45;specific models.
