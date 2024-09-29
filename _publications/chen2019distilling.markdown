---
layout: publication
title: 'Distilling Knowledge Learned In BERT For Text Generation'
authors: Chen Yen-chun, Gan Zhe, Cheng Yu, Liu Jingzhou, Liu Jingjing
conference: "Arxiv"
year: 2019
bibkey: chen2019distilling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1911.03829"}
  - {name: "Code", url: "https://github.com/ChenRocks/Distill-BERT-Textgen"}
tags: ['Applications', 'BERT', 'Has Code', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
Large-scale pre-trained language model such as BERT has achieved great success in language understanding tasks. However it remains an open question how to utilize BERT for language generation. In this paper we present a novel approach Conditional Masked Language Modeling (C-MLM) to enable the finetuning of BERT on target generation tasks. The finetuned BERT (teacher) is exploited as extra supervision to improve conventional Seq2Seq models (student) for better text generation performance. By leveraging BERTs idiosyncratic bidirectional nature distilling knowledge learned in BERT can encourage auto-regressive Seq2Seq models to plan ahead imposing global sequence-level supervision for coherent text generation. Experiments show that the proposed approach significantly outperforms strong Transformer baselines on multiple language generation tasks such as machine translation and text summarization. Our proposed model also achieves new state of the art on IWSLT German-English and English-Vietnamese MT datasets. Code is available at https://github.com/ChenRocks/Distill-BERT-Textgen."
