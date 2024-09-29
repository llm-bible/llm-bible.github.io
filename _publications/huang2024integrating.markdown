---
layout: publication
title: Integrating Multi45;scale Contextualized Information For Byte45;based Neural Machine Translation
authors: Huang Langlin, Feng Yang
conference: "Arxiv"
year: 2024
bibkey: huang2024integrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.19290"}
  - {name: "Code", url: "https://github.com/ictnlp/Multiscale&#45;Contextualization"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Model Architecture', 'RAG', 'Tokenization']
---
Subword tokenization is a common method for vocabulary building in Neural Machine Translation (NMT) models. However increasingly complex tasks have revealed its disadvantages. First a vocabulary cannot be modified once it is learned making it hard to adapt to new words. Second in multilingual translation the imbalance in data volumes across different languages spreads to the vocabulary exacerbating translations involving low45;resource languages. While byte45;based tokenization addresses these issues byte45;based models struggle with the low information density inherent in UTF45;8 byte sequences. Previous works enhance token semantics through local contextualization but fail to select an appropriate contextualizing scope based on the input. Consequently we propose the Multi45;Scale Contextualization (MSC) method which learns contextualized information of varying scales across different hidden state dimensions. It then leverages the attention module to dynamically integrate the multi45;scale contextualized information. Experiments show that MSC significantly outperforms subword45;based and other byte45;based methods in both multilingual and out45;of45;domain scenarios. Code can be found in https://github.com/ictnlp/Multiscale&#45;Contextualization.
