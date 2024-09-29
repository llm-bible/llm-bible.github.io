---
layout: publication
title: Adapterhub A Framework For Adapting Transformers
authors: Pfeiffer Jonas, Rücklé Andreas, Poth Clifton, Kamath Aishwarya, Vulić Ivan, Ruder Sebastian, Cho Kyunghyun, Gurevych Iryna
conference: "Arxiv"
year: 2020
bibkey: pfeiffer2020framework
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2007.07779"}
tags: ['BERT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
The current modus operandi in NLP involves downloading and fine45;tuning pre45;trained models consisting of millions or billions of parameters. Storing and sharing such large trained models is expensive slow and time45;consuming which impedes progress towards more general and versatile NLP methods that learn from and for many tasks. Adapters 45;45; small learnt bottleneck layers inserted within each layer of a pre45;trained model 45;45; ameliorate this issue by avoiding full fine45;tuning of the entire model. However sharing and integrating adapter layers is not straightforward. We propose AdapterHub a framework that allows dynamic stitching45;in of pre45;trained adapters for different tasks and languages. The framework built on top of the popular HuggingFace Transformers library enables extremely easy and quick adaptations of state45;of45;the45;art pre45;trained models (e.g. BERT RoBERTa XLM45;R) across tasks and languages. Downloading sharing and training adapters is as seamless as possible using minimal changes to the training scripts and a specialized infrastructure. Our framework enables scalable and easy access to sharing of task45;specific models particularly in low45;resource scenarios. AdapterHub includes all recent adapter architectures and can be found at https://AdapterHub.ml.
