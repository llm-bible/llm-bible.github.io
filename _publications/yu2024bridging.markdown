---
layout: publication
title: 'Antlm: Bridging Causal And Masked Language Models'
authors: Xinru Yu, Bin Guo, Shiwei Luo, Jie Wang, Tao Ji, Yuanbin Wu
conference: "Arxiv"
year: 2024
bibkey: yu2024bridging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.03275'}
tags: ['Attention Mechanism', 'Masked Language Model', 'Language Modeling', 'Transformer', 'RAG', 'Training Techniques', 'BERT', 'Model Architecture', 'Pretraining Methods']
---
Causal Language Modeling (CLM) and Masked Language Modeling (MLM) are two
mainstream learning paradigms based on Transformer networks, specifically the
Decoder-only and Encoder-only architectures. The strengths of each paradigm in
downstream tasks have shown a mix of advantages and disadvantages. In the past
BabyLM Challenge 2023, although the MLM paradigm achieved the best average
performance, the CLM paradigm demonstrated significantly faster convergence
rates. For the BabyLM Challenge 2024, we propose a novel language modeling
paradigm named \\(\textbf\{AntLM\}\\), which integrates both CLM and MLM to leverage
the advantages of these two classic paradigms. We chose the strict-small track
and conducted experiments on two foundation models: BabyLlama, representing
CLM, and LTG-BERT, representing MLM. During the training process for specific
foundation models, we alternate between applying CLM or MLM training objectives
and causal or bidirectional attention masks. Experimental results show that
combining the two pretraining objectives leverages their strengths, enhancing
overall training performance. Under the same epochs, \\(AntLM_\{BabyLlama\}\\)
improves Macro-average by 1%, and \\(AntLM_\{LTG-BERT\}\\) achieves a 2.2% increase
over the baselines.
