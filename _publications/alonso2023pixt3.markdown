---
layout: publication
title: PixT3 Pixel-based Table-To-Text Generation
authors: Alonso Iñigo, Agirre Eneko, Lapata Mirella
conference: "Arxiv"
year: 2023
bibkey: alonso2023pixt3
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09808"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Language Modeling', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques']
---
Table-to-text generation involves generating appropriate textual descriptions given structured tabular data. It has attracted increasing attention in recent years thanks to the popularity of neural network models and the availability of large-scale datasets. A common feature across existing methods is their treatment of the input as a string i.e. by employing linearization techniques that do not always preserve information in the table are verbose and lack space efficiency. We propose to rethink data-to-text generation as a visual recognition task removing the need for rendering the input in a string format. We present PixT3 a multimodal table-to-text model that overcomes the challenges of linearization and input size limitations encountered by existing models. PixT3 is trained with a new self-supervised learning objective to reinforce table structure awareness and is applicable to open-ended and controlled generation settings. Experiments on the ToTTo and Logic2Text benchmarks show that PixT3 is competitive and in some settings superior to generators that operate solely on text.
