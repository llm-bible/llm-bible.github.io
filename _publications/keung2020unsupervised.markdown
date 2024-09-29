---
layout: publication
title: "Unsupervised Bitext Mining And Translation Via Self-trained Contextual Embeddings"
authors: Keung Phillip, Salazar Julian, Lu Yichao, Smith Noah A.
conference: "Arxiv"
year: 2020
bibkey: keung2020unsupervised
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.07761"}
tags: ['Applications', 'BERT', 'Model Architecture', 'Training Techniques']
---
We describe an unsupervised method to create pseudo-parallel corpora for machine translation (MT) from unaligned text. We use multilingual BERT to create source and target sentence embeddings for nearest-neighbor search and adapt the model via self-training. We validate our technique by extracting parallel sentence pairs on the BUCC 2017 bitext mining task and observe up to a 24.5 point increase (absolute) in F1 scores over previous unsupervised methods. We then improve an XLM-based unsupervised neural MT system pre-trained on Wikipedia by supplementing it with pseudo-parallel text mined from the same corpus boosting unsupervised translation performance by up to 3.5 BLEU on the WMT14 French-English and WMT16 German-English tasks and outperforming the previous state-of-the-art. Finally we enrich the IWSLT15 English-Vietnamese corpus with pseudo-parallel Wikipedia sentence pairs yielding a 1.2 BLEU improvement on the low-resource MT task. We demonstrate that unsupervised bitext mining is an effective way of augmenting MT datasets and complements existing techniques like initializing with pre-trained contextual embeddings.
