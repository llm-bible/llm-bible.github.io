---
layout: publication
title: How Does BERT Answer Questions A Layer45;wise Analysis Of Transformer Representations
authors: Van Aken Betty, Winter Benjamin, Löser Alexander, Gers Felix A.
conference: "Arxiv"
year: 2019
bibkey: vanaken2019how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.04925"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Bidirectional Encoder Representations from Transformers (BERT) reach state45;of45;the45;art results in a variety of Natural Language Processing tasks. However understanding of their internal functioning is still insufficient and unsatisfactory. In order to better understand BERT and other Transformer45;based models we present a layer45;wise analysis of BERTs hidden states. Unlike previous research which mainly focuses on explaining Transformer models by their attention weights we argue that hidden states contain equally valuable information. Specifically our analysis focuses on models fine45;tuned on the task of Question Answering (QA) as an example of a complex downstream task. We inspect how QA models transform token vectors in order to find the correct answer. To this end we apply a set of general and QA45;specific probing tasks that reveal the information stored in each representation layer. Our qualitative analysis of hidden state visualizations provides additional insights into BERTs reasoning process. Our results show that the transformations within BERT go through phases that are related to traditional pipeline tasks. The system can therefore implicitly incorporate task45;specific information into its token representations. Furthermore our analysis reveals that fine45;tuning has little impact on the models semantic abilities and that prediction errors can be recognized in the vector representations of even early layers.
