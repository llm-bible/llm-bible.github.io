---
layout: publication
title: "Sensi-bert: Towards Sensitivity Driven Fine-tuning For Parameter-efficient BERT"
authors: Kundu Souvik, Sridhar Sharath Nittur, Szankin Maciej, Sundaresan Sairam
conference: "Arxiv"
year: 2023
bibkey: kundu2023sensi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.11764"}
tags: ['Applications', 'BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Large pre-trained language models have recently gained significant traction due to their improved performance on various down-stream tasks like text classification and question answering requiring only few epochs of fine-tuning. However their large model sizes often prohibit their applications on resource-constrained edge devices. Existing solutions of yielding parameter-efficient BERT models largely rely on compute-exhaustive training and fine-tuning. Moreover they often rely on additional compute heavy models to mitigate the performance gap. In this paper we present Sensi-BERT a sensitivity driven efficient fine-tuning of BERT models that can take an off-the-shelf pre-trained BERT model and yield highly parameter-efficient models for downstream tasks. In particular we perform sensitivity analysis to rank each individual parameter tensor that then is used to trim them accordingly during fine-tuning for a given parameter or FLOPs budget. Our experiments show the efficacy of Sensi-BERT across different downstream tasks including MNLI QQP QNLI SST-2 and SQuAD showing better performance at similar or smaller parameter budget compared to various alternatives.
