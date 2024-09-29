---
layout: publication
title: ELIT Emory Language And Information Toolkit
authors: He Han, Xu Liyan, Choi Jinho D.
conference: "Arxiv"
year: 2021
bibkey: he2021emory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.03903"}
  - {name: "Code", url: "https://github.com/emorynlp/elit"}
tags: ['Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Tokenization', 'Tools', 'Transformer']
---
We introduce ELIT the Emory Language and Information Toolkit which is a comprehensive NLP framework providing transformer-based end-to-end models for core tasks with a special focus on memory efficiency while maintaining state-of-the-art accuracy and speed. Compared to existing toolkits ELIT features an efficient Multi-Task Learning (MTL) model with many downstream tasks that include lemmatization part-of-speech tagging named entity recognition dependency parsing constituency parsing semantic role labeling and AMR parsing. The backbone of ELITs MTL framework is a pre-trained transformer encoder that is shared across tasks to speed up their inference. ELIT provides pre-trained models developed on a remix of eight datasets. To scale up its service ELIT also integrates a RESTful Client/Server combination. On the server side ELIT extends its functionality to cover other tasks such as tokenization and coreference resolution providing an end user with agile research experience. All resources including the source codes documentation and pre-trained models are publicly available at https://github.com/emorynlp/elit."
