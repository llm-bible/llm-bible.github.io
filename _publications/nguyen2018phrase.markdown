---
layout: publication
title: "Phrase-based Attentions"
authors: Nguyen Phi Xuan, Joty Shafiq
conference: "Arxiv"
year: 2018
bibkey: nguyen2018phrase
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1810.03444"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Most state-of-the-art neural machine translation systems despite being different in architectural skeletons (e.g. recurrence convolutional) share an indispensable feature the Attention. However most existing attention methods are token-based and ignore the importance of phrasal alignments the key ingredient for the success of phrase-based statistical machine translation. In this paper we propose novel phrase-based attention methods to model n-grams of tokens as attention entities. We incorporate our phrase-based attentions into the recently proposed Transformer network and demonstrate that our approach yields improvements of 1.3 BLEU for English-to-German and 0.5 BLEU for German-to-English translation tasks on WMT newstest2014 using WMT16 training data.
