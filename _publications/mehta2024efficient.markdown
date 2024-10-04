---
layout: publication
title: 'Openelm: An Efficient Language Model Family With Open Training And Inference Framework'
authors: Mehta Sachin, Sekhavat Mohammad Hossein, Cao Qingqing, Horton Maxwell, Jin Yanzi, Sun Chenfan, Mirzadeh Iman, Najibi Mahyar, Belenko Dmitry, Zatloukal Peter, Rastegari Mohammad
conference: "Arxiv"
year: 2024
bibkey: mehta2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.14619"}
  - {name: "Code", url: "https://github.com/apple/corenet"}
  - {name: "Code", url: "https://huggingface.co/apple/OpenELM"}
tags: ['Ethics And Bias', 'Fine Tuning', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
The reproducibility and transparency of large language models are crucial for advancing open research, ensuring the trustworthiness of results, and enabling investigations into data and model biases, as well as potential risks. To this end, we release OpenELM, a state-of-the-art open language model. OpenELM uses a layer-wise scaling strategy to efficiently allocate parameters within each layer of the transformer model, leading to enhanced accuracy. For example, with a parameter budget of approximately one billion parameters, OpenELM exhibits a 2.36&#37; improvement in accuracy compared to OLMo while requiring \\(2\times\\) fewer pre-training tokens. Diverging from prior practices that only provide model weights and inference code, and pre-train on private datasets, our release includes the complete framework for training and evaluation of the language model on publicly available datasets, including training logs, multiple checkpoints, and pre-training configurations. We also release code to convert models to MLX library for inference and fine-tuning on Apple devices. This comprehensive release aims to empower and strengthen the open research community, paving the way for future open research endeavors. Our source code along with pre-trained model weights and training recipes is available at \url\{https://github.com/apple/corenet\}. Additionally, \model models can be found on HuggingFace at: \url\{https://huggingface.co/apple/OpenELM\}.
