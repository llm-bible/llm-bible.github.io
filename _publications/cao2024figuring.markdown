---
layout: publication
title: Figuring Out Figures Using Textual References To Caption Scientific Figures
authors: Cao Stanley, Liu Kevin
conference: "Arxiv"
year: 2024
bibkey: cao2024figuring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.11008"}
tags: ['Attention Mechanism', 'BERT', 'Ethics And Bias', 'GPT', 'Model Architecture', 'Training Techniques']
---
Figures are essential channels for densely communicating complex ideas in scientific papers. Previous work in automatically generating figure captions has been largely unsuccessful and has defaulted to using single45;layer LSTMs which no longer achieve state45;of45;the45;art performance. In our work we use the SciCap datasets curated by Hsu et al. and use a variant of a CLIP+GPT45;2 encoder45;decoder model with cross45;attention to generate captions conditioned on the image. Furthermore we augment our training pipeline by creating a new dataset MetaSciCap that incorporates textual metadata from the original paper relevant to the figure such as the title abstract and in45;text references. We use SciBERT to encode the textual metadata and use this encoding alongside the figure embedding. In our experimentation with different models we found that the CLIP+GPT45;2 model performs better when it receives all textual metadata from the SciBERT encoder in addition to the figure but employing a SciBERT+GPT2 model that uses only the textual metadata achieved optimal performance.
