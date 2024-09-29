---
layout: publication
title: From PEFT To DEFT Parameter Efficient Finetuning For Reducing Activation Density In Transformers
authors: Runwal Bharat, Pedapati Tejaswini, Chen Pin-yu
conference: "Arxiv"
year: 2024
bibkey: runwal2024from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01911"}
tags: ['BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Transformer']
---
Pretrained Language Models (PLMs) have become the de facto starting point for fine45;tuning on downstream tasks. However as model sizes continue to increase traditional fine45;tuning of all the parameters becomes challenging. To address this parameter45;efficient fine45;tuning (PEFT) methods have gained popularity as a means to adapt PLMs effectively. In parallel recent studies have revealed the presence of activation sparsity within the intermediate outputs of the multilayer perceptron (MLP) blocks in transformers. Low activation density enables efficient model inference on sparsity45;aware hardware. Building upon this insight in this work we propose a novel density loss that encourages higher activation sparsity (equivalently lower activation density) in the pre45;trained models. We demonstrate the effectiveness of our approach by utilizing mainstream PEFT techniques including QLoRA LoRA Adapter and Prompt/Prefix Tuning to facilitate efficient model adaptation across diverse downstream tasks. Experiments show that our proposed method textbf123;DEFT125; (Density45;Efficient Fine45;Tuning) can consistently reduce activation density by up to textbf123;44.9437;125; on RoBERTa95;mathrm123;Large125; and by textbf123;53.1937;125; (encoder density) and textbf123;90.6037;125; (decoder density) on Flan45;T595;mathrm123;XXL125; (textbf123;11B125;) compared to PEFT using GLUE and QA (SQuAD) benchmarks respectively. We also introduce textbf123;ADA45;DEFT125; an adaptive variant of our DEFT approach which achieves significant memory and runtime savings during inference. For instance ADA45;DEFT reduces runtime by textbf123;8.7937;125;and memory usage by textbf123;17.4637;125; in Flan45;T595;mathrm123;XL125; and by textbf123;2.7937;125; and textbf123;2.5437;125; respectively in Flan45;T595;mathrm123;XXL125;. Additionally we showcase that DEFT works complementarily with quantized and pruned models.
