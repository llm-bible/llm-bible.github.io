---
layout: publication
title: "A Three Step Training Approach With Data Augmentation For Morphological Inflection"
authors: Szolnok Gabor, Barta Botond, Lakatos Dorina, Acs Judit
conference: "Arxiv"
year: 2021
bibkey: szolnok2021three
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.07006"}
tags: ['Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
We present the BME submission for the SIGMORPHON 2021 Task 0 Part 1 Generalization Across Typologically Diverse Languages shared task. We use an LSTM encoder-decoder model with three step training that is first trained on all languages then fine-tuned on each language families and finally finetuned on individual languages. We use a different type of data augmentation technique in the first two steps. Our system outperformed the only other submission. Although it remains worse than the Transformer baseline released by the organizers our model is simpler and our data augmentation techniques are easily applicable to new languages. We perform ablation studies and show that the augmentation techniques and the three training steps often help but sometimes have a negative effect.
