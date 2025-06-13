---
layout: publication
title: 'Data Whisperer: Efficient Data Selection For Task-specific LLM Fine-tuning Via Few-shot In-context Learning'
authors: Shaobo Wang, Xiangqi Jin, Ziming Wang, Jize Wang, Jiajun Zhang, Kaixin Li, Zichen Wen, Zhong Li, Conghui He, Xuming Hu, Linfeng Zhang
conference: "Arxiv"
year: 2025
bibkey: wang2025data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12212"}
  - {name: "Code", url: "https://github.com/gszfwsb/Data-Whisperer"}
tags: ['Fine-Tuning', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Fine-tuning large language models (LLMs) on task-specific data is essential for their effective deployment. As dataset sizes grow, efficiently selecting optimal subsets for training becomes crucial to balancing performance and computational costs. Traditional data selection methods often require fine-tuning a scoring model on the target dataset, which is time-consuming and resource-intensive, or rely on heuristics that fail to fully leverage the model's predictive capabilities. To address these challenges, we propose Data Whisperer, an efficient, training-free, attention-based method that leverages few-shot in-context learning with the model to be fine-tuned. Comprehensive evaluations were conducted on both raw and synthetic datasets across diverse tasks and models. Notably, Data Whisperer achieves superior performance compared to the full GSM8K dataset on the Llama-3-8B-Instruct model, using just 10% of the data, and outperforms existing methods with a 3.1-point improvement and a 7.4\\(\times\\) speedup. The code is available at https://github.com/gszfwsb/Data-Whisperer.
