---
layout: publication
title: Ca-lora&#58; Adapting Existing Lora For Compressed Llms To Enable Efficient Multi-tasking On Personal Devices
authors: Zhao Weilin, Huang Yuxiang, Han Xu, Liu Zhiyuan, Zhang Zhengyan, Li Kuai, Chen Chen, Yang Tao, Sun Maosong
conference: "Arxiv"
year: 2023
bibkey: zhao2023ca
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.07705"}
  - {name: "Code", url: "https://github.com/thunlp/CA-LoRA"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Quantization', 'RAG', 'Tools']
---
Recently there has been a demand to deploy Large Language Models (LLMs) on personal devices such as laptops and smartphones. These LLMs have different model variants when handling different tasks. However personal devices have limited resources and require reduced storage overhead. To address this there are two key methods available the first is model compression which compresses LLMs into smaller sizes; the second is LoRA which can transfer an LLM to other tasks with very few parameters avoiding the storage of multiple model variants in multi-task scenarios by only preserving LoRAs. However our experiments show that directly combining these two methods yields sub-optimal performance. Considering that the open-source community has already contributed many LoRAs to LLMs we propose to adapt these existing LoRAs from the LLMs to their compressed version and introduce a Compression-Aware LoRA (CA-LoRA) framework. We incorporate knowledge inheritance and recovery strategies to recover the lost knowledge caused by model compression. Experiment results demonstrate that CA-LoRA outperforms the vanilla LoRA methods applied to a compressed LLM and achieves comparable performance to the non-compressed LLM with existing LoRA modules. The source code of CA-LoRA is available at https://github.com/thunlp/CA-LoRA."
