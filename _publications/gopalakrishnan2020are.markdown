---
layout: publication
title: Are Neural Open-Domain Dialog Systems Robust to Speech Recognition Errors in the Dialog History An Empirical Study
authors: Gopalakrishnan Karthik, Hedayatnia Behnam, Wang Longshaokan, Liu Yang, Hakkani-tur Dilek
conference: "Arxiv"
year: 2020
bibkey: gopalakrishnan2020are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2008.07683"}
tags: ['Attention Mechanism', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Security', 'Training Techniques', 'Transformer']
---
Large end-to-end neural open-domain chatbots are becoming increasingly popular. However research on building such chatbots has typically assumed that the user input is written in nature and it is not clear whether these chatbots would seamlessly integrate with automatic speech recognition (ASR) models to serve the speech modality. We aim to bring attention to this important question by empirically studying the effects of various types of synthetic and actual ASR hypotheses in the dialog history on TransferTransfo a state-of-the-art Generative Pre-trained Transformer (GPT) based neural open-domain dialog system from the NeurIPS ConvAI2 challenge. We observe that TransferTransfo trained on written data is very sensitive to such hypotheses introduced to the dialog history during inference time. As a baseline mitigation strategy we introduce synthetic ASR hypotheses to the dialog history during training and observe marginal improvements demonstrating the need for further research into techniques to make end-to-end open-domain chatbots fully speech-robust. To the best of our knowledge this is the first study to evaluate the effects of synthetic and actual ASR hypotheses on a state-of-the-art neural open-domain dialog system and we hope it promotes speech-robustness as an evaluation criterion in open-domain dialog.
