---
layout: publication
title: Outlier45;efficient Hopfield Layers For Large Transformer45;based Models
authors: Hu Jerry Yao-chieh, Chang Pei-hsuan, Luo Robin, Chen Hong-yu, Li Weijian, Wang Wei-po, Liu Han
conference: "Arxiv"
year: 2024
bibkey: hu2024outlier
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03828"}
  - {name: "Code", url: "https://github.com/MAGICS&#45;LAB/OutEffHop&#125;&#123;GitHub&#125;;"}
  - {name: "Code", url: "https://huggingface.co/collections/magicslabnu/outeffhop&#45;6610fcede8d2cda23009a98f&#125;&#123;Hugging"}
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03828&#125;&#123;arXiv&#125;"}
tags: ['Attention Mechanism', 'BERT', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'RAG', 'Training Techniques', 'Transformer']
---
We introduce an Outlier45;Efficient Modern Hopfield Model (termed mathrm123;OutEffHop125;) and use it to address the outlier inefficiency problem of 123;training125; gigantic transformer45;based models. Our main contribution is a novel associative memory model facilitating textit123;outlier45;efficient125; associative memory retrievals. Interestingly this memory model manifests a model45;based interpretation of an outlier45;efficient attention mechanism (123;rm Softmax125;95;1) it is an approximation of the memory retrieval process of mathrm123;OutEffHop125;. Methodologically this allows us to introduce novel outlier45;efficient Hopfield layers as powerful alternatives to traditional attention mechanisms with superior post45;quantization performance. Theoretically the Outlier45;Efficient Modern Hopfield Model retains and improves the desirable properties of standard modern Hopfield models including fixed point convergence and exponential storage capacity. Empirically we demonstrate the efficacy of the proposed model across large45;scale transformer45;based and Hopfield45;based models (including BERT OPT ViT and STanHop45;Net) benchmarking against state45;of45;the45;art methods like mathtt123;Clipped95;Softmax125; and mathtt123;Gated95;Attention125;. Notably mathrm123;OutEffHop125; achieves an average reduction of 22+37; in average kurtosis and 26+37; in the maximum infinity norm of model outputs across four models. Code is available at href123;https://github.com/MAGICS&#45;LAB/OutEffHop&#125;&#123;GitHub&#125;; models are on href123;https://huggingface.co/collections/magicslabnu/outeffhop&#45;6610fcede8d2cda23009a98f&#125;&#123;Hugging Face Hub125;; future updates are on href123;https://arxiv.org/abs/2404.03828&#125;&#123;arXiv&#125;.
