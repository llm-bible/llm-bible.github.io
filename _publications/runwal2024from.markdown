---
layout: publication
title: 'From PEFT To DEFT: Parameter Efficient Finetuning For Reducing Activation Density In Transformers'
authors: Runwal Bharat, Pedapati Tejaswini, Chen Pin-yu
conference: "Arxiv"
year: 2024
bibkey: runwal2024from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01911"}
tags: ['BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques', 'Transformer']
---
'Pretrained Language Models (PLMs) have become the de facto starting point for fine-tuning on downstream tasks. However, as model sizes continue to increase, traditional fine-tuning of all the parameters becomes challenging. To address this, parameter-efficient fine-tuning (PEFT) methods have gained popularity as a means to adapt PLMs effectively. In parallel, recent studies have revealed the presence of activation sparsity within the intermediate outputs of the multilayer perceptron (MLP) blocks in transformers. Low activation density enables efficient model inference on sparsity-aware hardware. Building upon this insight, in this work, we propose a novel density loss that encourages higher activation sparsity (equivalently, lower activation density) in the pre-trained models. We demonstrate the effectiveness of our approach by utilizing mainstream PEFT techniques, including QLoRA, LoRA, Adapter, and Prompt/Prefix Tuning, to facilitate efficient model adaptation across diverse downstream tasks. Experiments show that our proposed method, \textbf\{DEFT\} (Density-Efficient Fine-Tuning), can consistently reduce activation density by up to \textbf\{44.94\&#37;\} on RoBERTa\(_\mathrm{Large}\) and by \textbf\{53.19\&#37;\} (encoder density) and \textbf\{90.60\&#37;\} (decoder density) on Flan-T5\(_\mathrm{XXL}\) (\textbf\{11B\}) compared to PEFT, using GLUE and QA (SQuAD) benchmarks respectively. We also introduce \textbf\{ADA-DEFT\}, an adaptive variant of our DEFT approach, which achieves significant memory and runtime savings during inference. For instance, ADA-DEFT reduces runtime by \textbf\{8.79\&#37;\}and memory usage by \textbf\{17.46\&#37;\} in Flan-T5\(_\mathrm{XL}\), and by \textbf\{2.79\&#37;\} and \textbf\{2.54\&#37;\} respectively in Flan-T5\(_\mathrm{XXL}\). Additionally, we showcase that DEFT works complementarily with quantized and pruned models.'
