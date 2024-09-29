---
layout: publication
title: Outlier-efficient Hopfield Layers For Large Transformer-based Models
authors: Hu Jerry Yao-chieh, Chang Pei-hsuan, Luo Robin, Chen Hong-yu, Li Weijian, Wang Wei-po, Liu Han
conference: "Arxiv"
year: 2024
bibkey: hu2024outlier
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03828"}
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03828}{arXiv"}
tags: ['Attention Mechanism', 'BERT', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'RAG', 'Training Techniques', 'Transformer']
---
We introduce an Outlier-Efficient Modern Hopfield Model (termed ) and use it to address the outlier inefficiency problem of training gigantic transformer-based models. Our main contribution is a novel associative memory model facilitating associative memory retrievals. Interestingly this memory model manifests a model-based interpretation of an outlier-efficient attention mechanism (rm Softmax_1) it is an approximation of the memory retrieval process of . Methodologically this allows us to introduce novel outlier-efficient Hopfield layers as powerful alternatives to traditional attention mechanisms with superior post-quantization performance. Theoretically the Outlier-Efficient Modern Hopfield Model retains and improves the desirable properties of standard modern Hopfield models including fixed point convergence and exponential storage capacity. Empirically we demonstrate the efficacy of the proposed model across large-scale transformer-based and Hopfield-based models (including BERT OPT ViT and STanHop-Net) benchmarking against state-of-the-art methods like and . Notably achieves an average reduction of 22+37; in average kurtosis and 26+37; in the maximum infinity norm of model outputs across four models. Code is available at ; future updates are on hrefhttps://arxiv.org/abs/2404.03828}{arXiv}.
