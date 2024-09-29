---
layout: publication
title: 'Openba: An Open-sourced 15B Bilingual Asymmetric Seq2seq Model Pre-trained From Scratch'
authors: Li Juntao, Tang Zecheng, Ding Yuyang, Wang Pinzheng, Guo Pei, You Wangjie, Qiao Dan, Chen Wenliang, Fu Guohong, Zhu Qiaoming, Zhou Guodong, Zhang Min
conference: "Arxiv"
year: 2023
bibkey: li2023open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.10706"}
  - {name: "Code", url: "https://huggingface.co/openBA"}
  - {name: "Code", url: "https://github.com/OpenNLG/openBA.git"}
tags: ['Fine Tuning', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Large language models (LLMs) with billions of parameters have demonstrated outstanding performance on various natural language processing tasks. This report presents OpenBA an open-sourced 15B bilingual asymmetric seq2seq model to contribute an LLM variant to the Chinese-oriented open-source model community. We enhance OpenBA with effective and efficient techniques as well as adopt a three-stage training strategy to train the model from scratch. Our solution can also achieve very competitive performance with only 380B tokens which is better than LLaMA-70B on the BELEBELE benchmark BLOOM-176B on the MMLU benchmark GLM-130B on the C-Eval (hard) benchmark. This report provides the main details to pre-train an analogous model including pre-training data processing Bilingual Flan data collection the empirical observations that inspire our model architecture design training objectives of different stages and other enhancement techniques. Additionally we also provide the fine-tuning details of OpenBA on four downstream tasks. We have refactored our code to follow the design principles of the Huggingface Transformers Library making it more convenient for developers to use and released checkpoints of different training stages at https://huggingface.co/openBA. More details of our project are available at https://github.com/OpenNLG/openBA.git."
