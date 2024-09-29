---
layout: publication
title: Character45;level Transformer45;based Neural Machine Translation
authors: Banar Nikolay, Daelemans Walter, Kestemont Mike
conference: "Arxiv"
year: 2020
bibkey: banar2020character
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.11239"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Neural machine translation (NMT) is nowadays commonly applied at the subword level using byte45;pair encoding. A promising alternative approach focuses on character45;level translation which simplifies processing pipelines in NMT considerably. This approach however must consider relatively longer sequences rendering the training process prohibitively expensive. In this paper we discuss a novel Transformer45;based approach that we compare both in speed and in quality to the Transformer at subword and character levels as well as previously developed character45;level models. We evaluate our models on 4 language pairs from WMT15 DE45;EN CS45;EN FI45;EN and RU45;EN. The proposed novel architecture can be trained on a single GPU and is 3437; percent faster than the character45;level Transformer; still the obtained results are at least on par with it. In addition our proposed model outperforms the subword45;level model in FI45;EN and shows close results in CS45;EN. To stimulate further research in this area and close the gap with subword45;level NMT we make all our code and models publicly available.
