---
layout: publication
title: On Task45;adaptive Pretraining For Dialogue Response Selection
authors: Lin Tzu-hsiang, Chi Ta-chung, Rumshisky Anna
conference: "Arxiv"
year: 2022
bibkey: lin2022task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.04073"}
tags: ['BERT', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Recent advancements in dialogue response selection (DRS) are based on the textit123;task45;adaptive pre45;training (TAP)125; approach by first initializing their model with BERT~cite123;devlin45;etal45;201945;bert125; and adapt to dialogue data with dialogue45;specific or fine45;grained pre45;training tasks. However it is uncertain whether BERT is the best initialization choice or whether the proposed dialogue45;specific fine45;grained learning tasks are actually better than MLM+NSP. This paper aims to verify assumptions made in previous works and understand the source of improvements for DRS. We show that initializing with RoBERTa achieve similar performance as BERT and MLM+NSP can outperform all previously proposed TAP tasks during which we also contribute a new state45;of45;the45;art on the Ubuntu corpus. Additional analyses shows that the main source of improvements comes from the TAP step and that the NSP task is crucial to DRS different from common NLU tasks.
