---
layout: publication
title: On Leveraging The Visual Modality For Neural Machine Translation
authors: Raunak Vikas, Choe Sang Keun, Lu Quanyang, Xu Yi, Metze Florian
conference: "Arxiv"
year: 2019
bibkey: raunak2019leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1910.02754"}
tags: ['Applications', 'Attention Mechanism', 'Merging', 'Model Architecture', 'Multimodal Models', 'RAG']
---
Leveraging the visual modality effectively for Neural Machine Translation (NMT) remains an open problem in computational linguistics. Recently Caglayan et al. posit that the observed gains are limited mainly due to the very simple short repetitive sentences of the Multi30k dataset (the only multimodal MT dataset available at the time) which renders the source text sufficient for context. In this work we further investigate this hypothesis on a new large scale multimodal Machine Translation (MMT) dataset How2 which has 1.57 times longer mean sentence length than Multi30k and no repetition. We propose and evaluate three novel fusion techniques each of which is designed to ensure the utilization of visual context at different stages of the Sequence-to-Sequence transduction pipeline even under full linguistic context. However we still obtain only marginal gains under full linguistic context and posit that visual embeddings extracted from deep vision models (ResNet for Multi30k ResNext for How2) do not lend themselves to increasing the discriminativeness between the vocabulary elements at token level prediction in NMT. We demonstrate this qualitatively by analyzing attention distribution and quantitatively through Principal Component Analysis arriving at the conclusion that it is the quality of the visual embeddings rather than the length of sentences which need to be improved in existing MMT datasets.
