---
layout: publication
title: Capturing Document Context Inside Sentence45;level Neural Machine Translation Models With Self45;training
authors: Mansimov Elman, Melis Gábor, Yu Lei
conference: "Arxiv"
year: 2020
bibkey: mansimov2020capturing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2003.05259"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Training Techniques']
---
Neural machine translation (NMT) has arguably achieved human level parity when trained and evaluated at the sentence45;level. Document45;level neural machine translation has received less attention and lags behind its sentence45;level counterpart. The majority of the proposed document45;level approaches investigate ways of conditioning the model on several source or target sentences to capture document context. These approaches require training a specialized NMT model from scratch on parallel document45;level corpora. We propose an approach that doesnt require training a specialized model on parallel document45;level corpora and is applied to a trained sentence45;level NMT model at decoding time. We process the document from left to right multiple times and self45;train the sentence45;level model on pairs of source sentences and generated translations. Our approach reinforces the choices made by the model thus making it more likely that the same choices will be made in other sentences in the document. We evaluate our approach on three document45;level datasets NIST Chinese45;English WMT19 Chinese45;English and OpenSubtitles English45;Russian. We demonstrate that our approach has higher BLEU score and higher human preference than the baseline. Qualitative analysis of our approach shows that choices made by model are consistent across the document.
