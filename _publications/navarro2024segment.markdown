---
layout: publication
title: Segment-Based Interactive Machine Translation for Pre-trained Models
authors: Navarro Angel, Casacuberta Francisco
conference: "Arxiv"
year: 2024
bibkey: navarro2024segment
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.06990"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Pre-trained large language models (LLM) are starting to be widely used in many applications. In this work we explore the use of these models in interactive machine translation (IMT) environments. In particular we have chosen mBART (multilingual Bidirectional and Auto-Regressive Transformer) and mT5 (multilingual Text-to-Text Transfer Transformer) as the LLMs to perform our experiments. The system generates perfect translations interactively using the feedback provided by the user at each iteration. The Neural Machine Translation (NMT) model generates a preliminary hypothesis with the feedback and the user validates new correct segments and performs a word correction--repeating the process until the sentence is correctly translated. We compared the performance of mBART mT5 and a state-of-the-art (SoTA) machine translation model on a benchmark dataset regarding user effort Word Stroke Ratio (WSR) Key Stroke Ratio (KSR) and Mouse Action Ratio (MAR). The experimental results indicate that mBART performed comparably with SoTA models suggesting that it is a viable option for this field of IMT. The implications of this finding extend to the development of new machine translation models for interactive environments as it indicates that some novel pre-trained models exhibit SoTA performance in this domain highlighting the potential benefits of adapting these models to specific needs.
