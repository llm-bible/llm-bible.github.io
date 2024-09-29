---
layout: publication
title: Openelm An Efficient Language Model Family With Open Training And Inference Framework
authors: Mehta Sachin, Sekhavat Mohammad Hossein, Cao Qingqing, Horton Maxwell, Jin Yanzi, Sun Chenfan, Mirzadeh Iman, Najibi Mahyar, Belenko Dmitry, Zatloukal Peter, Rastegari Mohammad
conference: "Arxiv"
year: 2024
bibkey: mehta2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.14619"}
  - {name: "Code", url: "https://github.com/apple/corenet&#125;"}
  - {name: "Code", url: "https://huggingface.co/apple/OpenELM&#125;"}
tags: ['Ethics And Bias', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
The reproducibility and transparency of large language models are crucial for advancing open research ensuring the trustworthiness of results and enabling investigations into data and model biases as well as potential risks. To this end we release OpenELM a state45;of45;the45;art open language model. OpenELM uses a layer45;wise scaling strategy to efficiently allocate parameters within each layer of the transformer model leading to enhanced accuracy. For example with a parameter budget of approximately one billion parameters OpenELM exhibits a 2.3637; improvement in accuracy compared to OLMo while requiring 2× fewer pre45;training tokens. Diverging from prior practices that only provide model weights and inference code and pre45;train on private datasets our release includes the complete framework for training and evaluation of the language model on publicly available datasets including training logs multiple checkpoints and pre45;training configurations. We also release code to convert models to MLX library for inference and fine45;tuning on Apple devices. This comprehensive release aims to empower and strengthen the open research community paving the way for future open research endeavors. Our source code along with pre45;trained model weights and training recipes is available at url123;https://github.com/apple/corenet&#125;. Additionally model models can be found on HuggingFace at url123;https://huggingface.co/apple/OpenELM&#125;.
