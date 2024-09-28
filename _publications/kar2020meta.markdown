---
layout: publication
title: Meta-Context Transformers for Domain-Specific Response Generation
authors: Kar Debanjana, Samanta Suranjana, Azad Amar Prakash
conference: "Arxiv"
year: 2020
bibkey: kar2020meta
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.05572"}
tags: ['Transformer', 'Arxiv', 'Language Modeling', 'Model Architecture', 'GPT']
---
Despite the tremendous success of neural dialogue models in recent years it suffers a lack of relevance diversity and some times coherence in generated responses. Lately transformer-based models such as GPT-2 have revolutionized the landscape of dialogue generation by capturing the long-range structures through language modeling. Though these models have exhibited excellent language coherence they often lack relevance and terms when used for domain-specific response generation. In this paper we present DSRNet (Domain Specific Response Network) a transformer-based model for dialogue response generation by reinforcing domain-specific attributes. In particular we extract meta attributes from context and infuse them with the context utterances for better attention over domain-specific key terms and relevance. We study the use of DSRNet in a multi-turn multi-interlocutor environment for domain-specific response generation. In our experiments we evaluate DSRNet on Ubuntu dialogue datasets which are mainly composed of various technical domain related dialogues for IT domain issue resolutions and also on CamRest676 dataset which contains restaurant domain conversations. Trained with maximum likelihood objective our model shows significant improvement over the state-of-the-art for multi-turn dialogue systems supported by better BLEU and semantic similarity (BertScore) scores. Besides we also observe that the responses produced by our model carry higher relevance due to the presence of domain-specific key attributes that exhibit better overlap with the attributes of the context. Our analysis shows that the performance improvement is mostly due to the infusion of key terms along with dialogues which result in better attention over domain-relevant terms. Other contributing factors include joint modeling of dialogue context with the domain-specific meta attributes and topics.
