---
layout: publication
title: "GRAM: Global Reasoning For Multi-page VQA"
authors: Blau Tsachi, Fogel Sharon, Ronen Roi, Golts Alona, Ganz Roy, Avraham Elad Ben, Aberdam Aviad, Tsiper Shahar, Litman Ron
conference: "Arxiv"
year: 2024
bibkey: blau2024global
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.03411"}
tags: ['Applications', 'Ethics And Bias', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
The increasing use of transformer-based large language models brings forward the challenge of processing long sequences. In document visual question answering (DocVQA) leading methods focus on the single-page setting while documents can span hundreds of pages. We present GRAM a method that seamlessly extends pre-trained single-page models to the multi-page setting without requiring computationally-heavy pretraining. To do so we leverage a single-page encoder for local page-level understanding and enhance it with document-level designated layers and learnable tokens facilitating the flow of information across pages for global reasoning. To enforce our model to utilize the newly introduced document tokens we propose a tailored bias adaptation method. For additional computational savings during decoding we introduce an optional compression stage using our compression-transformer (C-Former)reducing the encoded sequence length thereby allowing a tradeoff between quality and latency. Extensive experiments showcase GRAMs state-of-the-art performance on the benchmarks for multi-page DocVQA demonstrating the effectiveness of our approach.
