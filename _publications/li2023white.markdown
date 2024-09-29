---
layout: publication
title: White45;box Multi45;objective Adversarial Attack On Dialogue Generation
authors: Li Yufei, Li Zexin, Gao Yingfan, Liu Cong
conference: "Arxiv"
year: 2023
bibkey: li2023white
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.03655"}
tags: ['Model Architecture', 'Pretraining Methods', 'Security', 'Transformer']
---
Pre45;trained transformers are popular in state45;of45;the45;art dialogue generation (DG) systems. Such language models are however vulnerable to various adversarial samples as studied in traditional tasks such as text classification which inspires our curiosity about their robustness in DG systems. One main challenge of attacking DG models is that perturbations on the current sentence can hardly degrade the response accuracy because the unchanged chat histories are also considered for decision45;making. Instead of merely pursuing pitfalls of performance metrics such as BLEU ROUGE we observe that crafting adversarial samples to force longer generation outputs benefits attack effectiveness 45;45; the generated responses are typically irrelevant lengthy and repetitive. To this end we propose a white45;box multi45;objective attack method called DGSlow. Specifically DGSlow balances two objectives 45;45; generation accuracy and length via a gradient45;based multi45;objective optimizer and applies an adaptive searching mechanism to iteratively craft adversarial samples with only a few modifications. Comprehensive experiments on four benchmark datasets demonstrate that DGSlow could significantly degrade state45;of45;the45;art DG models with a higher success rate than traditional accuracy45;based methods. Besides our crafted sentences also exhibit strong transferability in attacking other models.
