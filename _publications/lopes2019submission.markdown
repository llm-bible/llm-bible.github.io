---
layout: publication
title: 'Unbabel''s Submission To The WMT2019 APE Shared Task: Bert-based Encoder-decoder For Automatic Post-editing'
authors: António V. Lopes, M. Amin Farajian, Gonçalo M. Correia, Jonay Trenous, André F. T. Martins
conference: "Arxiv"
year: 2019
bibkey: lopes2019submission
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/1905.13068'}
tags: ['WMT', 'Training Techniques', 'BERT', 'Model Architecture', 'Tools', 'Applications']
---
This paper describes Unbabel's submission to the WMT2019 APE Shared Task for
the English-German language pair. Following the recent rise of large, powerful,
pre-trained models, we adapt the BERT pretrained model to perform Automatic
Post-Editing in an encoder-decoder framework. Analogously to dual-encoder
architectures we develop a BERT-based encoder-decoder (BED) model in which a
single pretrained BERT encoder receives both the source src and machine
translation tgt strings. Furthermore, we explore a conservativeness factor to
constrain the APE system to perform fewer edits. As the official results show,
when trained on a weighted combination of in-domain and artificial training
data, our BED system with the conservativeness penalty improves significantly
the translations of a strong Neural Machine Translation system by \\(-0.78\\) and
\\(+1.23\\) in terms of TER and BLEU, respectively. Finally, our submission
achieves a new state-of-the-art, ex-aequo, in English-German APE of NMT.
