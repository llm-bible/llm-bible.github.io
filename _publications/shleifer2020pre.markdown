---
layout: publication
title: Pre45;trained Summarization Distillation
authors: Shleifer Sam, Rush Alexander M.
conference: "Arxiv"
year: 2020
bibkey: shleifer2020pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.13002"}
  - {name: "Code", url: "http://tiny.cc/4iy0tz"}
tags: ['Applications', 'BERT', 'Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Recent state45;of45;the45;art approaches to summarization utilize large pre45;trained Transformer models. Distilling these models to smaller student models has become critically important for practical use; however there are many different distillation methods proposed by the NLP literature. Recent work on distilling BERT for classification and regression tasks shows strong performance using direct knowledge distillation. Alternatively machine translation practitioners distill using pseudo45;labeling where a small model is trained on the translations of a larger model. A third simpler approach is to shrink and fine45;tune (SFT) which avoids any explicit distillation by copying parameters to a smaller student model and then fine45;tuning. We compare these three approaches for distillation of Pegasus and BART the current and former state of the art pre45;trained summarization models and find that SFT outperforms knowledge distillation and pseudo45;labeling on the CNN/DailyMail dataset but under45;performs pseudo45;labeling on the more abstractive XSUM dataset. PyTorch Code and checkpoints of different sizes are available through Hugging Face transformers here http://tiny.cc/4iy0tz.
