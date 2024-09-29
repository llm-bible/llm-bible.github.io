---
layout: publication
title: Non45;autoregressive Neural Machine Translation A Call For Clarity
authors: Schmidt Robin M., Pires Telmo, Peitz Stephan, Lööf Jonas
conference: "Arxiv"
year: 2022
bibkey: schmidt2022non
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.10577"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Pretraining Methods']
---
Non45;autoregressive approaches aim to improve the inference speed of translation models by only requiring a single forward pass to generate the output sequence instead of iteratively producing each predicted token. Consequently their translation quality still tends to be inferior to their autoregressive counterparts due to several issues involving output token interdependence. In this work we take a step back and revisit several techniques that have been proposed for improving non45;autoregressive translation models and compare their combined translation quality and speed implications under third45;party testing environments. We provide novel insights for establishing strong baselines using length prediction or CTC45;based architecture variants and contribute standardized BLEU chrF++ and TER scores using sacreBLEU on four translation tasks which crucially have been missing as inconsistencies in the use of tokenized BLEU lead to deviations of up to 1.7 BLEU points. Our open45;sourced code is integrated into fairseq for reproducibility.
