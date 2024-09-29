---
layout: publication
title: Co45;training Improves Prompt45;based Learning For Large Language Models
authors: Lang Hunter, Agrawal Monica, Kim Yoon, Sontag David
conference: "Arxiv"
year: 2022
bibkey: lang2022co
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2202.00828"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
We demonstrate that co45;training (Blum amp; Mitchell 1998) can improve the performance of prompt45;based learning by using unlabeled data. While prompting has emerged as a promising paradigm for few45;shot and zero45;shot learning it is often brittle and requires much larger models compared to the standard supervised setup. We find that co45;training makes it possible to improve the original prompt model and at the same time learn a smaller downstream task45;specific model. In the case where we only have partial access to a prompt model (e.g. output probabilities from GPT45;3 (Brown et al. 2020)) we learn a calibration model over the prompt outputs. When we have full access to the prompt models gradients but full finetuning remains prohibitively expensive (e.g. T0 (Sanh et al. 2021)) we learn a set of soft prompt continuous vectors to iteratively update the prompt model. We find that models trained in this manner can significantly improve performance on challenging datasets where there is currently a large gap between prompt45;based learning and fully45;supervised models.
