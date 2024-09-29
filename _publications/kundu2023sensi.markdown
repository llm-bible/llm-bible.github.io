---
layout: publication
title: Sensi45;bert Towards Sensitivity Driven Fine45;tuning For Parameter45;efficient BERT
authors: Kundu Souvik, Sridhar Sharath Nittur, Szankin Maciej, Sundaresan Sairam
conference: "Arxiv"
year: 2023
bibkey: kundu2023sensi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.11764"}
tags: ['Applications', 'BERT', 'Model Architecture', 'Training Techniques']
---
Large pre45;trained language models have recently gained significant traction due to their improved performance on various down45;stream tasks like text classification and question answering requiring only few epochs of fine45;tuning. However their large model sizes often prohibit their applications on resource45;constrained edge devices. Existing solutions of yielding parameter45;efficient BERT models largely rely on compute45;exhaustive training and fine45;tuning. Moreover they often rely on additional compute heavy models to mitigate the performance gap. In this paper we present Sensi45;BERT a sensitivity driven efficient fine45;tuning of BERT models that can take an off45;the45;shelf pre45;trained BERT model and yield highly parameter45;efficient models for downstream tasks. In particular we perform sensitivity analysis to rank each individual parameter tensor that then is used to trim them accordingly during fine45;tuning for a given parameter or FLOPs budget. Our experiments show the efficacy of Sensi45;BERT across different downstream tasks including MNLI QQP QNLI SST45;2 and SQuAD showing better performance at similar or smaller parameter budget compared to various alternatives.
