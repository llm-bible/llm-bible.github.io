---
layout: publication
title: 'Zamba: A Compact 7B SSM Hybrid Model'
authors: Glorioso Paolo, Anthony Quentin, Tokpanov Yury, Whittington James, Pilault Jonathan, Ibrahim Adam, Millidge Beren
conference: "Arxiv"
year: 2024
bibkey: glorioso2024compact
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16712"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Transformer']
---
'In this technical report, we present Zamba, a novel 7B SSM-transformer hybrid model which achieves competitive performance against leading open-weight models at a comparable scale. Zamba is trained on 1T tokens from openly available datasets and is the best non-transformer model at this scale. Zamba pioneers a unique architecture combining a Mamba backbone with a single shared attention module, thus obtaining the benefits of attention at minimal parameter cost. Due to its architecture, Zamba is significantly faster at inference than comparable transformer models and requires substantially less memory for generation of long sequences. Zamba is pretrained in two phases: the first phase is based on existing web datasets, while the second one consists of annealing the model over high-quality instruct and synthetic datasets, and is characterized by a rapid learning rate decay. We open-source the weights and all checkpoints for Zamba, through both phase 1 and annealing phases.'
