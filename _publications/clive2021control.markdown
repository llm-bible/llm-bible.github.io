---
layout: publication
title: Control Prefixes For Parameter45;efficient Text Generation
authors: Clive Jordan, Cao Kris, Rei Marek
conference: "Arxiv"
year: 2021
bibkey: clive2021control
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.08329"}
tags: ['Applications', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Transformer']
---
Prefix45;tuning is a powerful lightweight technique for adapting a large pre45;trained language model to a downstream application. However it uses the same dataset45;level tuned prompt for all examples in the dataset. We extend this idea and propose a dynamic method Control Prefixes which allows for the inclusion of conditional input45;dependent information combining the benefits of prompt tuning and controlled generation. The method incorporates attribute45;level learnable representations into different layers of a pre45;trained transformer allowing for the generated text to be guided in a particular direction. We provide a systematic evaluation of the technique and apply it to five datasets from the GEM benchmark for natural language generation (NLG). Although the aim is to develop a parameter45;efficient model we show Control Prefixes can even outperform full fine45;tuning methods. We present state45;of45;the45;art results on several data45;to45;text datasets including WebNLG.
