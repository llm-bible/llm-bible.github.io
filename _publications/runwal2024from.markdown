---
layout: publication
title: From PEFT to DEFT Parameter Efficient Finetuning for Reducing Activation Density in Transformers
authors: Runwal Bharat, Pedapati Tejaswini, Chen Pin-yu
conference: "Arxiv"
year: 2024
bibkey: runwal2024from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01911"}
tags: ['ARXIV', 'BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
Pretrained Language Models (PLMs) have become the de facto starting point for fine-tuning on downstream tasks. However as model sizes continue to increase traditional fine-tuning of all the parameters becomes challenging. To address this parameter-efficient fine-tuning (PEFT) methods have gained popularity as a means to adapt PLMs effectively. In parallel recent studies have revealed the presence of activation sparsity within the intermediate outputs of the multilayer perceptron (MLP) blocks in transformers. Low activation density enables efficient model inference on sparsity-aware hardware. Building upon this insight in this work we propose a novel density loss that encourages higher activation sparsity (equivalently lower activation density) in the pre-trained models. We demonstrate the effectiveness of our approach by utilizing mainstream PEFT techniques including QLoRA LoRA Adapter and Prompt/Prefix Tuning to facilitate efficient model adaptation across diverse downstream tasks. Experiments show that our proposed method (Density-Efficient Fine-Tuning) can consistently reduce activation density by up to on RoBERTa_ and by (encoder density) and (decoder density) on Flan-T5_ () compared to PEFT using GLUE and QA (SQuAD) benchmarks respectively. We also introduce an adaptive variant of our DEFT approach which achieves significant memory and runtime savings during inference. For instance ADA-DEFT reduces runtime by and memory usage by in Flan-T5_ and by and respectively in Flan-T5_. Additionally we showcase that DEFT works complementarily with quantized and pruned models.
