---
layout: publication
title: Visualgpt Data-efficient Adaptation Of Pretrained Language Models For Image Captioning
authors: Chen Jun, Guo Han, Yi Kai, Li Boyang, Elhoseiny Mohamed
conference: "Arxiv"
year: 2021
bibkey: chen2021data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2102.10407"}
  - {name: "Code", url: "https://github.com/Vision-CAIR/VisualGPT"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
The ability to quickly learn from a small quantity oftraining data widens the range of machine learning applications. In this paper we propose a data-efficient image captioning model VisualGPT which leverages the linguistic knowledge from a large pretrained language model(LM). A crucial challenge is to balance between the use of visual information in the image and prior linguistic knowledge acquired from pretraining. We designed a novel self-resurrecting encoder-decoder attention mechanism to quickly adapt the pretrained LM as the language decoder ona small amount of in-domain training data. The proposed self-resurrecting activation unit produces sparse activations but has reduced susceptibility to zero gradients. We train the proposed model VisualGPT on 0.137; 0.537; and 137; of MSCOCO and Conceptual Captions training data. Under these conditions we outperform the best baseline model by up to 10.837; CIDEr on MS COCO and upto 5.437; CIDEr on Conceptual Captions. Further Visual-GPT achieves the state-of-the-art result on IU X-ray a medical report generation dataset. To the best of our knowledge this is the first work that improves data efficiency of image captioning by utilizing LM pretrained on unimodal data. Our code is available at https://github.com/Vision-CAIR/VisualGPT."
