---
layout: publication
title: Diagnosing Transformers in Task-Oriented Semantic Parsing
authors: Desai Shrey, Aly Ahmed
conference: "Arxiv"
year: 2021
bibkey: desai2021diagnosing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2105.13496"}
tags: ['Ethics And Bias', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Modern task-oriented semantic parsing approaches typically use seq2seq transformers to map textual utterances to semantic frames comprised of intents and slots. While these models are empirically strong their specific strengths and weaknesses have largely remained unexplored. In this work we study BART and XLM-R two state-of-the-art parsers across both monolingual and multilingual settings. Our experiments yield several key results transformer-based parsers struggle not only with disambiguating intents/slots but surprisingly also with producing syntactically-valid frames. Though pre-training imbues transformers with syntactic inductive biases we find the ambiguity of copying utterance spans into frames often leads to tree invalidity indicating span extraction is a major bottleneck for current parsers. However as a silver lining we show transformer-based parsers give sufficient indicators for whether a frame is likely to be correct or incorrect making them easier to deploy in production settings.
