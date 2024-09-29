---
layout: publication
title: The Stability45;efficiency Dilemma Investigating Sequence Length Warmup For Training GPT Models
authors: Li Conglong, Zhang Minjia, He Yuxiong
conference: "Arxiv"
year: 2021
bibkey: li2021stability
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2108.06084"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Recent works have demonstrated great success in pre45;training large45;scale autoregressive language models on massive GPUs. To reduce the wall45;clock training time a common practice is to increase the batch size and learning rate. However such practice is often brittle and leads to a so45;called stability45;efficiency dilemma increasing the batch sizes and learning rates leads to better training efficiency but can also result in training instability leading to poor generalization accuracy or failed runs. To better understand this phenomenon we conduct an in45;depth analysis on large45;scale pre45;training experiments replicating the GPT45;2 model. We find that there is a strong correlation between training instability and extreme values of gradient variance and that samples with long sequence lengths contribute to these extreme gradient variance values especially at the beginning of the training indicating that long sequence length can be a main source of training instability. Based on the analysis we present a Sequence Length Warmup method that aims to solve the training stability45;efficiency dilemma. Experiments replicating GPT45;2 models show that our approach enables stable training with 8x larger batch size and 4x larger learning rate whereas the baseline approach struggles with training instability. To achieve the same or better zero45;shot evaluation results our method reduces the required number of training tokens and wall clock time by up to 2.2x and 3.7x respectively. Experiments replicating GPT45;3 model (125M) show that our approach enables stable training with 8x larger batch size and 40x larger learning rate and retains 9937; of the zero45;shot accuracy on 11 tasks using 10x less data and 17x less time compared to the original GPT45;3 training recipe while the baseline diverges under the same settings and only retain 9537; of accuracy under lower learning rate.
