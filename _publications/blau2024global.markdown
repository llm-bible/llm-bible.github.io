---
layout: publication
title: GRAM Global Reasoning For Multi45;page VQA
authors: Blau Tsachi, Fogel Sharon, Ronen Roi, Golts Alona, Ganz Roy, Avraham Elad Ben, Aberdam Aviad, Tsiper Shahar, Litman Ron
conference: "Arxiv"
year: 2024
bibkey: blau2024global
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.03411"}
tags: ['Applications', 'Ethics And Bias', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
The increasing use of transformer45;based large language models brings forward the challenge of processing long sequences. In document visual question answering (DocVQA) leading methods focus on the single45;page setting while documents can span hundreds of pages. We present GRAM a method that seamlessly extends pre45;trained single45;page models to the multi45;page setting without requiring computationally45;heavy pretraining. To do so we leverage a single45;page encoder for local page45;level understanding and enhance it with document45;level designated layers and learnable tokens facilitating the flow of information across pages for global reasoning. To enforce our model to utilize the newly introduced document tokens we propose a tailored bias adaptation method. For additional computational savings during decoding we introduce an optional compression stage using our compression45;transformer (C45;Former)reducing the encoded sequence length thereby allowing a tradeoff between quality and latency. Extensive experiments showcase GRAMs state45;of45;the45;art performance on the benchmarks for multi45;page DocVQA demonstrating the effectiveness of our approach.
