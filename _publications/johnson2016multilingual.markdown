---
layout: publication
title: "Google's Multilingual Neural Machine Translation System: Enabling Zero-shot Translation"
authors: Johnson Melvin, Schuster Mike, Le Quoc V., Krikun Maxim, Wu Yonghui, Chen Zhifeng, Thorat Nikhil, Viégas Fernanda, Wattenberg Martin, Corrado Greg, Hughes Macduff, Dean Jeffrey
conference: "Arxiv"
year: 2016
bibkey: johnson2016multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1611.04558"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
We propose a simple solution to use a single Neural Machine Translation (NMT) model to translate between multiple languages. Our solution requires no change in the model architecture from our base system but instead introduces an artificial token at the beginning of the input sentence to specify the required target language. The rest of the model which includes encoder decoder and attention remains unchanged and is shared across all languages. Using a shared wordpiece vocabulary our approach enables Multilingual NMT using a single model without any increase in parameters which is significantly simpler than previous proposals for Multilingual NMT. Our method often improves the translation quality of all involved language pairs even while keeping the total number of model parameters constant. On the WMT14 benchmarks a single multilingual model achieves comparable performance for English(rightarrow)French and surpasses state-of-the-art results for English(rightarrow)German. Similarly a single multilingual model surpasses state-of-the-art results for French(rightarrow)English and German(rightarrow)English on WMT14 and WMT15 benchmarks respectively. On production corpora multilingual models of up to twelve language pairs allow for better translation of many individual pairs. In addition to improving the translation quality of language pairs that the model was trained with our models can also learn to perform implicit bridging between language pairs never seen explicitly during training showing that transfer learning and zero-shot translation is possible for neural translation. Finally we show analyses that hints at a universal interlingua representation in our models and show some interesting examples when mixing languages.
