---
layout: publication
title: Bootstrapping Vision45;language Learning With Decoupled Language Pre45;training
authors: Jian Yiren, Gao Chongyang, Vosoughi Soroush
conference: "Arxiv"
year: 2023
bibkey: jian2023bootstrapping
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.07063"}
  - {name: "Code", url: "https://github.com/yiren&#45;jian/BLIText"}
tags: ['Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques', 'Transformer']
---
We present a novel methodology aimed at optimizing the application of frozen large language models (LLMs) for resource45;intensive vision45;language (VL) pre45;training. The current paradigm uses visual features as prompts to guide language models with a focus on determining the most relevant visual features for corresponding text. Our approach diverges by concentrating on the language component specifically identifying the optimal prompts to align with visual features. We introduce the Prompt45;Transformer (P45;Former) a model that predicts these ideal prompts which is trained exclusively on linguistic data bypassing the need for image45;text pairings. This strategy subtly bifurcates the end45;to45;end VL training process into an additional separate stage. Our experiments reveal that our framework significantly enhances the performance of a robust image45;to45;text baseline (BLIP45;2) and effectively narrows the performance gap between models trained with either 4M or 129M image45;text pairs. Importantly our framework is modality45;agnostic and flexible in terms of architectural design as validated by its successful application in a video learning task using varied base modules. The code will be made available at https://github.com/yiren&#45;jian/BLIText.
