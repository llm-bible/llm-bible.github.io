---
layout: publication
title: Categorizing Semantic Representations for Neural Machine Translation
authors: Yin Yongjing, Li Yafu, Meng Fandong, Zhou Jie, Zhang Yue
conference: "Arxiv"
year: 2022
bibkey: yin2022categorizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.06709"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Modern neural machine translation (NMT) models have achieved competitive performance in standard benchmarks. However they have recently been shown to suffer limitation in compositional generalization failing to effectively learn the translation of atoms (e.g. words) and their semantic composition (e.g. modification) from seen compounds (e.g. phrases) and thus suffering from significantly weakened translation performance on unseen compounds during inference. We address this issue by introducing categorization to the source contextualized representations. The main idea is to enhance generalization by reducing sparsity and overfitting which is achieved by finding prototypes of token representations over the training set and integrating their embeddings into the source encoding. Experiments on a dedicated MT dataset (i.e. CoGnition) show that our method reduces compositional generalization error rates by 24 error reduction. In addition our conceptually simple method gives consistently better results than the Transformer baseline on a range of general MT datasets.
